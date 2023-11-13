# DeepLoL
This program is not for personal or commercial use. This is a WIP and should *not* be used as-is.  
This program is purely a personal project to learn Python, Deep Learning, and Boost.

Credits:
Winstealer Made by bckd00r.  
Xepher Fork Made by TopZoozle.  
Original LViewPlus made by CNLouisLiu.  
LViewPlus64 made by ImbaMDT.  

## Current Status: **NONFUNCTIONAL**  
This repository is essentially unedited from the original source as of 11/12/23.  
If you have concerns about this project please contact me through Github.

### Building

You need Visual Studio 2019 to compile this.
Dependencies:
  1. python39: dlls and includes are already in project. You need to install python 3.9 for 64bits (Make sure you check the Add to PATH checkbox in the installer: https://www.python.org/ftp/python/3.9.0/python-3.9.0-amd64.exe)
  3. aws-lambda: dlls and includes are already in project (was used for authentication)
  3. directx 11: Must install directx end user runtimes: https://www.microsoft.com/en-us/download/details.aspx?id=35 .Extract this and run dxsetup
  4. boost::python. Due to the size of the boost libraries you must compile boost::python yourself:
      1. Download boost 1.75.0 (https://www.boost.org/users/history/version_1_75_0.html)
      2. Unarchive it in LViewPlus64/boost
  5. You are done now compile the app on Release x64 (you need to compile boost::python on debug to compile on debug, which I didn't).
 ### Setup
 All LView & LView python scripts configurations reside in config.ini file. First you must set the path to the scripts folder with the following config (you can find the config.ini in LView folder):
 
  `::scriptsFolder=\<folder\>`
## How can i use Formatter?

First, you will need to do "pip install black" because the python definitions need to be defined in every way. It doesn't see some files, but that's okay. Then put it to "Gameplayscripts" and type "python format.py".

