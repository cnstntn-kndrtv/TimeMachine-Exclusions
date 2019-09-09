# TimeMachine-Exclusions

<img src="006-timeline.png" height="50px" width="50px">

Simple automator app for list exclusions form TimeMachine backups

## Why?
I found nice utility [Asimov](https://github.com/stevegrunwell/asimov) that helps to exclude some 'dev' folders from backup.  
For list all of excluded folders you can run one simple command `sudo mdfind \"com_apple_backup_excludeItem = 'com.apple.backupd'\"`.  
But I always forgetting all of that wired shell commands.  
This little app just runs that script, creates list of all excluded folders and writes it to new TexEdit window.  

icon from flaticon.com

