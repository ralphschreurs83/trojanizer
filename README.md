[![Version](https://img.shields.io/badge/Trojanizer-v1.0-brightgreen.svg?maxAge=259200)]()
[![Stage](https://img.shields.io/badge/Release-Beta-orange.svg)]()
[![Build](https://img.shields.io/badge/Supported_OS-Linux-orange.svg)]()
[![AUR](https://img.shields.io/aur/license/yaourt.svg)]()


## TROJANIZER
    Version release : v1.0
    Author : pedro ubuntu  [ r00t-3xp10it ]
    Codename: Troia_Revisited
    Distros Supported : Ubuntu, Kali, Mint, Parrot OS
    Suspicious-Shell-Activity (SSA) RedTeam develop @2017

![venom shellcode v1.0.13](http://i.cubeupload.com/e0e0V1.png)

<br />

## FRAMEWORK DESCRIPTION
    The Trojanizer tool uses WinRAR (SFX) to compress two files input by user,
    and transforms it into an SFX executable(.exe) archive. The sfx archive when
    executed it will run bouth files (our payload and the legit appl at the same time).

    To make the archive less suspicious at execution time, trojanizer will replace
    the default icon(.ico) of the sfx file with a user-selected one, it also allow
    us to execute a program/command before the extraction/execution of the two files.
    To activate the Presetup funtion: [ settings -> PRE_SETUP=ON ]

   **'This tool will not build real trojans, but from target perpective it will behave like one'**.<br />
   (execute the payload in background, while the legit application also executes in foreground).

<br /><br />

## DEPENDENCIES (backend applications)
    Zenity | Wine | WinRAr.exe (wine)
    "Trojanizer.sh will download/install all dependencies as they are needed"


## PAYLOADS (agents) ACCEPTED
    .exe | .bat | .vbs | .ps1


## LEGIT APPLICATIONS ACCEPTED
    .exe | .bat | .vbs | .ps1 | .jpg | .bmp | .doc | .ppt | etc ..
    "All applications that windows system can auto-execute"

<br /><br />

## DOWNLOAD/INSTALL
    1º - Download framework from github
         git clone https://github.com/r00t-3xp10it/trojanizer.git

    2º - Set files execution permitions
         cd trojanizer
         sudo chmod +x *.sh

    3º - config framework
         nano settings

    4º - Run main tool
         sudo ./Trojanizer.sh



## Framework Screenshots
![venom shellcode v1.0.13](http://i.cubeupload.com/6yNJGG4.png)<br />
![venom shellcode v1.0.13-Beta](http://i.cubeupload.com/n7N6xee.png)<br />
![venom shellcode v1.0.13-Beta](http://i.cubeupload.com/jWpj7f3.png)<br />


<br />


### -- Suspicious-Shell-Activity© (SSA) RedTeam develop @2017 --


