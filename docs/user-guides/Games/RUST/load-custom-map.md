#How to load custom map on your RUST Server

It is possible to have a custom map on the RUST Server apart from the original ones and it's rather easy to load one. Just follow these simple steps:

1.  Upload your custom .map file to Dropbox
2.  Once uploaded, copy the download link
3.  Go to your RUST service on the Fragnet Game Panel
4.  Navigate to Commandline Manager ⇾ Custom commandline
5.  Edit your existing Custom commandline or create a new one
6.  Under the +levelurl parameter paste your download link  
    Example: https://www.dropbox.com/s/<randomcharacters>/<mapname>.map?dl=0
7.  Change the dl=0 to dl=1 in that link  
    Example: https://www.dropbox.com/s/<randomcharacters>/<mapname>.map?dl=1
8.  Once done, tick the checkbox before the +levelurl parameter and press Save.
9.  Restart the server so the changes can take effect.

You have now successfully added a custom map to your RUST server!

!!! info "INFO"
    If you are just trying to load a custom map that is already uploaded by a third party, you should start from step 3.