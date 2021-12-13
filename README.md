<h1 align="center">Handbrake-Installer</h1>
<h3 align="center">Compile Latest Handbrake Easily!</h3>


<p>The instructions to compile the latest handbrake version are easy to follow from their website: https://handbrake.fr/docs/en/latest/developer/install-dependencies-ubuntu.html but require time that an average user does not have and may even mess up the process. So use this repo for automatic dependency installation and compiling of handbrake :) </p>
  
  
## Features

- [x] Installs basic dependencies
- [x] Installs QSV dependencies (Intel Quick Sync Video)
- [x] Installs GTK GUI build dependencies
- [x] Builds handbrake with QSV support
  
## Usage

Only works with Ubuntu and all it's variants! Run the following command in Terminal:

```
sudo apt update && sudo apt -y install autoconf automake autopoint appstream build-essential cmake git libass-dev libbz2-dev libfontconfig1-dev libfreetype6-dev libfribidi-dev libharfbuzz-dev libjansson-dev liblzma-dev libmp3lame-dev libnuma-dev libogg-dev libopus-dev libsamplerate-dev libspeex-dev libtheora-dev libtool libtool-bin libturbojpeg0-dev libvorbis-dev libx264-dev libxml2-dev libvpx-dev m4 make meson nasm ninja-build patch pkg-config python tar zlib1g-dev libva-dev libdrm-dev gstreamer1.0-libav intltool libappindicator-dev libdbus-glib-1-dev libglib2.0-dev libgstreamer1.0-dev libgstreamer-plugins-base1.0-dev libgtk-3-dev libgudev-1.0-dev libnotify-dev libwebkit2gtk-4.0-dev
git clone --depth=1 https://github.com/HandBrake/HandBrake.git && cd HandBrake && ./configure --launch-jobs=$(nproc) --launch --enable-qsv && sudo make --directory=build install
```
  
Everything will be done automatically :)
