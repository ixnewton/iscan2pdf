# iscan2pdf
Wrapper script for iscan for mutipage PDFs. 

This script was started when I needed to scan multiple documents to a single PDF file. There are some solutions available but since I rely on Epson's Iscan application to work with a multifunction Epson printer (WF2530) on a local network I tried here to work around the functional single shot scanning application.

The script simply sets up a folder under ~/Documents/Scans for each scan using an entered scan label then runs iscan. When enough numbered .tiff files (default01.tiff, default02.tiff etc) are created closing iscan will generate the final pdf file with the given scan label. 

A working installation of iscan is required and zenity for script popup dialogues. Both are available in Linux distribution repositories. I install scripts like this to the standard /usr/local/bin (chmod 755) and manually create a start menu entry to run it.




