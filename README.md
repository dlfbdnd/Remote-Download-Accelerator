# Remote-Download-Accelerator
A NodeJS application that turns your computer/VPS into a download relay station. Supports Direct (http(s), ftp) and YouTube (video) download.
Tested OK on Fedora 28 and Ubuntu 18.04, should support other *Linux* distributions as well. 
### Prerequisites
- youtube-dl
  - `sudo apt install youtube-dl`
- ffmpeg
  - `sudo apt install ffmpeg`
- wget
  - `sudo apt install wget`
- nodejs
  - `sudo apt install nodejs`
- unzip
  - `sudo apt install unzip`
- git (optional)
  - `sudo apt install git`
### Getting started
```bash
wget https://github.com/dlfbdnd/Remote-Download-Accelerator/releases/download/0.7.18/rmdl-v0.7.18.zip
unzip rmdl*.zip
cd rmdl*/
sudo node index.js
```
