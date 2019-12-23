# SuccessionRestore

Alternative to Cydia Eraser that is much easier to update. Downloads and mounts rootfilesystem DMG for your iOS version. Then moves files from mounted DMG to the main filesystem.

Special thanks to @pwn20wndstuff, @PsychoTea, @Cryptiiic, @4ppleCracker for their respective contributions to this project.

This project is free (and always will be), donations are never required but highly appreciated: https://paypal.me/SamGardner4

*rsync used in accordance with gpl3*

## Installation

Succession is currently available from:

- My repo, https://samgisaninja.github.io
- Dynastic, https://repo.dynastic.co (default repository on all jailbreaks, iOS 11 or higher)
- BigBoss, https://apt.thebigboss.org/repofiles (default repository on all jailbreaks except jailbreaks made by coolstar)

## Compiling

*I really dont anticipate that anyone will ever attempt to compile this project... but... here goes* ¯\\\_(ツ)_/¯

Requires macOS, and probably a fairly recent version of it. 

Requires `fakeroot`, `ldid`, and `dpkg`. If you dont have them already, they can be easily installed using [homebrew](https://brew.sh):

`brew install fakeroot`

`brew install ldid`

`brew install dpkg`

Once you have the dependencies, compiling is fairly easy, just run the compile script in the root directory of this project, it will automatically create a .deb file for installation. You can also use the "install" script to automate the installation process, this requires OpenSSH or dropbear or some alternative of it and SFTP to be available on your device (OpenSSH has both). The install script used to be a part of the compile script, but I got annoyed by it so I split the two. I might delete the install script some day, idk.
