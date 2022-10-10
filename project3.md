### STEP 1 -BACKEND CONFIGURATION
update ubuntu 
```
sudo apt update
```
upgrade Ubuntu 
```
sudo apt upgrade
```
Lets get the location of Node.js software from **Ubuntu repositories**.
```
curl -fsSL https://deb.nodesource.com/setup_18.x | sudo -E bash -
```
*install Node.js on the server*
```
sudo apt-get install -y nodejs
```
**Note**: The command above installs both nodejs and npm. NPM is a package manager for Node like apt for Ubuntu, it is used to install Node modules & packages and to manage dependency conflicts
