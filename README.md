<h1 align="center">Handbrake-Installer</h1>
<h3 align="center">Compile Latest Handbrake Easily!</h3>


<p>The instructions to compile the latest handbrake version are easy to follow from their website: https://handbrake.fr/docs/en/latest/developer/install-dependencies-ubuntu.html but require time that an average user does not have and may even mess up the process. So use this repo for automatic dependency installation and compiling of handbrake :)
  
  
## Features

- [x] Installs basic dependencies
- [x] Installs QSV dependencies (Intel Quick Sync Video)
- [x] Installs GTK GUI build dependencies
- [x] Builds handbrake for you
  
## Usage

Only works with Ubuntu and all it's variants! Run the following command in Terminal:

```
git clone --depth=1 https://github.com/xerohackcom/Handbrake-Installer.git && cd Handbrake-Installer && chmod +x run.sh
```
```
sudo bash run.sh
```
  
Everything will be done automatically :)
