# GitWrap
Windows Wrapper for Linux git executable.

Windows Subsystem for Linux is pretty awesome, but managing two separate git environment is not. So, here is a quick hack for that.

GitWrap is currently a Proof Of Concept solution and is in no way complete or reliable. It has been tested with Android Studio and seems to work pretty well when set up correctly.

## Requirements
- Windows Subsystem for Linux must be installed. 
- Git should be installed in the Linux environment.
- Supports x64 variant of Windows only. 

## Installation
Download the latest release or GitWrap.exe and save it anywhere you want. Then configure Android Studio's git executable path and make it point to GitWrap.exe. Android Studio should now be using git from your Linux Sub System on Windows 10.

It should work with other IDE's as well but I can only vouch for what I've tested myself.

