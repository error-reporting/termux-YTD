# termux-YTD
termux-YTD+ script to install yt-dlp,  ffmpeg or as a companion to termux desktop https://github.com/sabamdarif/termux-desktop

To use this script,

Installation (one time)

Download termux APK from F-Droid or GitHub since play store version is deprecated.
Open termux, and paste the following command

```
curl -sL "https://gist.githubusercontent.com/error-reporting/b087ec0cb8ed4d143843666702235c82/raw/dc63c1381b10c2421521da302df2351b926566bc/install.sh" -O && chmod a+rx install.sh && ./install.sh
```

or use this if you already downloaded the script

```
./install.sh
```

When apt upgrade ask you allow it by typing y then press enter

when Configuration file '/data/data/com.termux/files/usr/etc/apt/sources.list' and Configuration file '/data/data/com.termux/files/usr/etc/bash.bashrc' ask you type y then press enter 

the app will ask for storage access, allow it by tapping on 'Yes'.

if already installed then invoke it with

```
~/bin/termux-url-opener
```

Usage
Tap on share for the video that you wanted to download, and choose termux, download will start automatically. (for this method to work, you might need to give "Draw over other apps" permission to termux) or invoke
```
~/bin/termux-url-opener "https://www.youtube.com/watch?v=VIDEO_ID"
```
replace
> https://www.youtube.com/watch?v=VIDEO_ID with your actual video link
