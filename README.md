# How to use Parallels Desktop for free on macOS
### Step by step guide how to use parallels desktop 18 for free via shortcut **[unlimited time]**
### Or just download shell script version.


## At first download PD 18 Pro from official website.
> **https://www.parallels.com/directdownload/pd/?mode=trial**
#### If the version have changed and the guide isn't working anymore here is the reserve link to the .dmg image
> **https://drive.google.com/file/d/1CX4MgUVmY0kbH3-lmbLAGnBhdkm30eJa/view?usp=sharing**

## For next save shortcut on mac
> **https://www.icloud.com/shortcuts/c33c2a0395874bc0a1da450134fc9257**

## Some changes need to be held in shorcut
### As soon as we need to use sudo[super user] the app will request the password to change date and time
##### Don't worry date and time will automaticly be change to today's

#### At first create passwd.txt file and save in there your mac's password
#### Once done open Shortcuts app and edit the shortcut
#### cd Users/$YOUR_USERNAME/
> ex: cd Users/admin
#### cd $FOLDER_WHERE_DOC_WAS_PUT
> ex: cd Downloads
#### sudo -S date -u 0101043020 < ~/$PATH_OF_THE_TXT_FILE
> ex: sudo -S date -u 0101043020 < ~/Downloads/passwd.txt

## **The same for last part of shortcut**
#### It must look something like this.
> https://drive.google.com/file/d/164BTb17kdhbwVHq-XRAO6z7dffxHkk46/view?usp=sharing

## Once everything is done close Shortcuts app and run the shortcut.
### If something have gone wrong contact me.
