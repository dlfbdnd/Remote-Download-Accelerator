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
### Getting started
```bash
git clone https://github.com/dlfbdnd/Remote-Download-Accelerator.git
cd Remote-Download-Accelerator
unzip rmdl*.zip
mkdir -p /var/www/html/
mv rmdl*/ /var/www/html/
cd /var/www/html/rmdl*/
sudo node index.js
```
