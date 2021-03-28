# NCSDownloader
A simple bash script that can download songs from NCS.io

## Prerequisites
[Pup](https://github.com/ericchiang/pup)

## How to use NCSDownloader
Download this repo
```
git clone https://github.com/tif24048/NCSDownloader.git
```
Make the script executable
```
chmod +x ncs
```
Next execute the script and type the name of a NCS song, for example Invicible
```
./ncs invincible
```

You can also download multiple songs at the same time, just separate them with a space
```
./ncs invincible withoutyou
```

## Installation
You can use this script from any directory by moving it to /usr/local/bin
```
mv ncs /usr/local/bin
```
Then make it executable
```
chmod 777 /usr/local/bin/ncs
```
Both commands must be run as root

Because so many NCS songs have duplicate names you might not be able to download certain songs through this script.
