#Troubleshooting InsaneLimits reset on restart

On rare occasions, if you are running InsaneLimits plugin on your Procon Layer, upon restart the rules will reset. This happens if you have multiple InsaneLimits config files especially if Procon Layer was moved from one IP to another.

Start by editing the following:  
_Configs/IP\_Port/InsaneLimits.cfg_

Once that config is opened, look for the following line:  
`” procon.protected.plugins.setVariable "InsaneLimits" "limits_file ”`

The line should continue with a BASE64 encoded string.

Copy the text after `BASE64:` and paste it on [Base64decode](https://www.base64decode.org/) to decode it.

![InsaneLimits](../images/insanelimits.png)

When successfully decoded, you will see the output and see if the IP\_PORT (IP of the Battlefield server and its RCON port) is wrong.

If it’s wrong, head back to the file manager and go to Plugins/BF4 folder. In there you should see 2 InsaneLimits config files, one for the old IP and one of the new IP. The new file should be 0kb so just copy everything from the "old" file.

When you placed the content from the “old” file to a new config that should be used, switch to “Encode” tab on [Base64decode](https://www.base64decode.org/ ).  
Place the following line, with the correct (yours) IP of your Battlefield server and the RCON Port.  
`” Plugins\BF4\InsaneLimits_IP_RCONPORT.conf ”`and press ENCODE.

![InsaneLimits2](../images/insanelimits2.png)

Head back to _Configs/IP\_Port/InsaneLimits.cfg_ and change the BASE64 string to the one generated above. Save and restart the Procon layer. It should then no longer reset the limits set!