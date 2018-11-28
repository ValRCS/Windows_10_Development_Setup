# Windows_10_Development_Setup
Guide for setting up Windows 10 for development

## Windows 10 (Pro) installed

* Activate Windows with a key
* https://ninite.com grab installer for Firefox(or/and Chrome),VLC,Notepad++,VSCode,PuTTY (other tools such as SumatraPDF,qbtorrent, Filezilla,Dropbox etc can be helpful) avoid Python here until Ninite migrates to 3.+ version!
* TODO get rid of bloatware(Candy Crush, Minecraft etc etc)
* ublock Origin for Firefox/Chrome

## GIT installation
* GIT download from https://git-scm.com/downloads for Windows direct link is: https://git-scm.com/download/win
* keep all default choices except choose Notepad++ instead of vim as an editor(that is unless you like vim)

### GIT config
https://git-scm.com/book/en/v2/Getting-Started-First-Time-Git-Setup
* $ git config --global user.name "John Doe"
* $ git config --global user.email johndoe@example.com

## Python

* https://www.python.org/downloads/ 3.+ version
* install,choose add to PATH, optional enable long path names(256+) chars
### Python setup
from CMD/PS/Bash:
* pip list
* python -m pip install --upgrade pip

## VS Code setup

* install Python extension https://marketplace.visualstudio.com/items?itemName=ms-python.python

### For Powershell Enviroment you might need this:
* $env:path="$env:Path;C:\Users\Admin\AppData\Local\Programs\Python\Python37-32\" the last being the directory where your Python is installed
see: https://stackoverflow.com/questions/714877/setting-windows-powershell-path-variable

For running scripts (risky if you dont trust your scripts)
* Set-ExecutionPolicy Unrestricted from administrator Powershell


