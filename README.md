# Remote-Download-Accelerator
A NodeJS application that turns your computer/VPS into a download relay station. Supports http, https, ftp, YouTube, and Xiami using youtube-dl, you-get and wget.
### Requirements
- youtube-dl
  - `sudo apt install youtube-dl`
- you-get
  - `pip3 install you-get`
- wget
  - `sudo apt install wget`
- nodejs
  - `sudo apt install nodejs`
### Getting started
```bash
unzip rmdl.zip
cd rmdl
sudo node index.js #Requires root if port is 80 by default
```
