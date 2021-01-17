# Trevors-Cleanup-Script
This repository contains batch files used to automate computer cleanup using built in Windows utilities.

## User Manual:
   *Download the Zip file, the whole repository, or the TCS folder
   *Extract the files anywhere you'd like
   *Double click the "Run TCS V2.0" Shortcut
   *When asked Y/N type "Y" and hit enter
   *Everytime the script restarts you will need to login
   *Later in the script an Admin prompt will pop up, please hit "Yes"
   *Wait until the script says its done
   *Make sure to hit ENTER to close the script!
## Utilities Used

#### Temporary File Cleaner
   * cleanmgr
   * del %temp%
#### Defragment C Drive
   * defrag c:
#### CHKDSK
   * CHKDSK /f
#### SFC
   * SFC /scannow
#### DISM
   * dism /online /cleanup-image /restorehealth
   
# Git Command
`git clone https://github.com/DroTron/Numerical-Methods-Algorithms`
*  Clones entire repository
*  add `~/FOLDER/SUBFOLDER` after PROGRAM.m to clone to specific folder
   * Ex: `git clone https://github.com/DroTron/Numerical-Methods-Algorithms ~/NumericalMethods`
   * to clone repository to a folder in home named NumericalMethods
