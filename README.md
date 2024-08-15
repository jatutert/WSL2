# Ubuntu Config 

Bash shell script for configuring linux so that demonstrations can be given based on it. 
For example, you should think of demonstrations of the products e.g. Docker, Ansible and also MiniKube. 
I myself use this for education and therefore the approach is also personal or educational use.   

### Version 1

Version 1 was born out of frustration that every time Ubuntu Linux had to be reconfigured within Windows WSL. 
The script does a predetermined configuration of WSL environment. This saved a lot of time.
Based on version 1, a number of spin offs were created for very specialized environments (e.g. minikube). 
These are based on version 1, but adapted to this environment. 
Both version 1 and the spin offs can still be used, but they are no longer maintained.  

### Version 2

Version 2 is based on version 1. 
The biggest change from version 1 is the main menu from which the user can make choices instead of fixed configuration. 
Another major change is the merging of the version 1 spin offs into 1 version. 

Available options are:
- Install Ubuntu updates (option 1) 
- Install Docker Community Edition and Docker Compose 
- Install Cockpit (option 3) 
- Install Minikube (option 5) 
- Install Ansible (demo environment is also installed) 
- Install GNOME GUI (option 6)
- Create Folder Structure and scripts (option 2) 

Script Language in current version is only Dutch. 

### Version 3

Version 3 is an attempt to create the ultimate configuration script that no longer depends on the distribution of Linux. 
Making it completely independent of distribution is not there yet because version 3 is currently working on Ubuntu Linux. 
However, it has been updated to the latest version (24.04) of the LTS release. 
It is planned to support Alpine and Debian in the future. 
But first the focus is on making a very good script that works flawlessly on Ubuntu. 
So that later this can be converted to other distributions. 
Completely new to version 3 is the implementation of startup parameter for the script. 
The script then goes to work based on this parameter. 
Version 2 has remained a bit, because you can also start the script with the parameter menu and then menu is shown similar to version 2. 




