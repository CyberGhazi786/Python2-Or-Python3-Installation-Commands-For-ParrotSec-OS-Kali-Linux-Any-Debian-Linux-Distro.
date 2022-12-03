# Python2-Or-Python3-Installation-Commands-For-ParrotSec-OS-Kali-Linux-Any-Debian-Linux-Distro.
Python2 Or Python3 Installation Commands For ParrotSec OS / Kali Linux / Any Debian Linux Distro.



✔️Procedure 1: Check for the current version of Python in your machine 
Step 1. Run this command : python (or) python3  –V in terminal
Step 2. Run this command : python3  –V  (You may find the version if this version is not installed 
    
✔️Procedure 2: Run a Upgrade of Kali Linux Distro 
Step 1. Use the command : apt-get –y upgrade (On a terminal)

✔️Procedure 3: Install Python 
Step 1. Download the python 3.8.2 from the website -  https://www.python.org/ 
Step 2. Extract the download file to the Kali and then navigate to the folder in Terminal (or) Open the extracted folder and right click and select open terminal here
Step 3. Once you are inside the python 3.8.2 folder run this command :  ./configure
Step 4. Once completed above process please run the command : make 
Step 5. Once completed above process please run the command : make install 

✔️Procedure 4: Check installed version of python 
Step 1. Please check the version of python : python3  –V  
Step 2. To check if the python is working fine do test it by running a simple print command : print (“Hello Cloud Guru”) you should get a output – Hello Cloud Guru 

✔️Procedure 5: Install PIP 
Step 1. To install the PIP : apt-get install –y python3 –pip 

✔️Procedure 6: For Building essential components (Optional) 
Step 1. Run the command as part of a healthy process : apt-get install build-essential libssl-dev libffi-dev python-dev
