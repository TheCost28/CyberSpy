# CyberSpy
Para Teemux

Intalacion!

CyberSpy - Espía Cibernético
Hacking Tool Suite for Android in Termux (No root)

This tool can only be executed in Termux.

Preview in Termux
CyberSpy

Requirements
Updated Termux application.
Android 7 or higher.
Minimum 100MB of available storage.
Download Termux F-Droid
Note: It is not recommended to use the Termux application that is available in "Google Play Store" because the developers no longer maintain this app and therefore it is outdated. Termux still receives updates on another platform called "F-Droid" so download the app with the following link: Termux F-Droid

Installation in Termux
Update Termux repositories.

yes|pkg update && pkg upgrade
Grant storage permissions to Termux.

termux-setup-storage
Install "git" version control software.

yes|pkg install git
Clone github repository.

git clone https://github.com/Darkmux/cyberspy
Access the cloned "cyberspy" folder.

cd cyberspy
Grant execute permissions to all files with extension (.sh).

chmod 777 *.sh
Run the installer.

bash cyberspy.sh
