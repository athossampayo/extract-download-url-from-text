# extract-download-url-from-text
It is a simple script that picks a big text message with urls of files in it and extract the links, saves a TXT file and also downloads the files to a folder.

### Needs to install manually the *WGET module*

## USAGE
1. You need to have a file on the script directory root with some message and some url in it. When running the script will ask you to input the filename.
2. It will generate a file **"url-list.txt"** on the directory (if you run multiple times with different messages, the script will append to this file).
3. After that it will run wget and download files to a new paste named **"wgetfiles"** on its directory.


## FUTURE GOALS

- [x] Translate to English.  
- [ ] Make wget use multiple processing.  
- [x] Use as set to save the urls to text file so it doesnt append duplicate urls.  
- [ ] Clean the terminal messages shown.  
- [ ] Automatic install WGET module.  
- [ ] Using the *set()* made an error in the output file with the url links and it needs a fix. (reading with 'r+' mode will overwrite the old data)

