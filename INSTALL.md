Installation instructions
=========================

More detailed installation instructions can be found in this file. This will use the official package uploaded to pip.

1.- Verifying the Python and pip installation
---------------------------------------------

First of all, on any system we should verify that we have a Python 2.7 installation and a Pip installation setup properly. Opening the terminal or the powershell, we can try the following to check your python installation:
```
python --version
```

If you get errors at this point or the Python version is not appeating, your system is not yet prepared. You will need to install Python 2.7 from the official website:
```
https://www.python.org/downloads/
```
Follow the installation steps for your system. Note that in one step of the Windows installation process you WILL NEED to manually add c:\Python27 and C:\Python27\scripts to the system. Try again after completing this task.

Now it's the turn of the Package manager. Check that you have the pip version installed:
```
pip --version
```
If you get any errors at this point, you have several options:
* If your running Ubuntu or Debian-like systems, try sudo apt-get install python-pip
* In any case you can always download <https://bootstrap.pypa.io/get-pip.py> and install it manually. In Windows-like systems, you do NOT need to type sudo. 
```
# Going to the downloads folder
python get-pip.py
```
You can do it at a time in Linux and MacOS systems:
```
# Downloading
wget https://bootstrap.pypa.io/get-pip.py
# Installing as root
sudo python get-pip.py
```
Try again and check if the new pip version is installed.


2 - Installing the application
------------------------------

TO-DO.

3 - Testing the installation
-----------------------------

TO-DO.

4 - Updating the framework
--------------------------

TO-DO.

