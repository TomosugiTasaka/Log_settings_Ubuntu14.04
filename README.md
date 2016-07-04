# Ubuntu14.04 log setting
## Purpose
This is log to keep in mind.  
But I write this log in midstream. So they are probably not right.   

## Installed
There are my installed applications.
* **Android studio**  
This is tool to make application of android OS.  
  * Season  
  2015/11/25  
  * Version  
  android studio 1.5
  * Download Site  
  [**Developers** adndroid studio](https://developer.android.com/sdk/index.html)  
  * Packages
    * Android Studio IDE  
    IDE means Integrated Development Environment. It have text editor and compiler, debugger, etc.  
    * Android SDK Tools
    SDK means Software Development Kit. You want to make application of android.  
    * Android 6.0  
    * Emulator  
  * Install  
    1. Download "All Android Studio Package" for Linux.  
    `{home}/Downloads/android-studio-ide-***-linux.zip`  
    2. This zip file has been frozen. So give dissolved this where you want to install.    
    Write this in your command line.  
    `unzip android-studio-ide-***-linux.zip`  
    In your directory, it should have been made this directory.  
    `android-studio`
    3. Install Android Studio. Write this command.  
    `./android-studio/bin/studio.sh`  
    If you write this command, open window of setup from command line.  
  * Desktop file  
  If you leave the default, you must use from command line. You will want to search from dash.  
    * How to solve this problem  
    You have to make this file.  
    `{home}/.local/share/applications/android-studio.desktop`  
    ```
    [Desktop Entry]
    Version=1.0
    Type=Application
    Name=android-studio
    Comment=This is android studio
    Icon=/android-studio/bin/studio.ico
    Exec=/android-studio/bin/studio.sh
    Terminal=false
    StartupNotify=false
    Categories=Utility;Application;
    ```  
    You will be able to search Android Studio from dash.

* **SmartGit**  
This is software of git. I think you help using git.  
  * Season  
  2016/7/4  
  * Version  
 7.1.3  
  * Homepage  
[Git Client SmartGit](http://www.syntevo.com/smartgit/)
