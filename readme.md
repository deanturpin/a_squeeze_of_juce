* https://www.juce.com/get-juce/download
* https://www.juce.com/doc/tutorial_new_projucer_project

```
> cd JUCE/
> ls
juce-huckleberry-linux.zip
> ll
total 16752
drwxrwxr-x  2 dev dev     4096 Aug 22 12:44 ./
drwxr-xr-x 98 dev dev     4096 Aug 22 12:44 ../
-rw-rw-r--  1 dev dev 17137799 Aug 22 12:44 juce-huckleberry-linux.zip
> 
> 
> 
> unzip juce-huckleberry-linux.zip 

ls
JUCE  juce-huckleberry-linux.zip

```

* Continuous rebuild (not for Linux)
* Nice full screen

# You'll need an IDE
https://launchpad.net/~damien-moore/+archive/ubuntu/codeblocks-stable
```bash
sudo apt install codeblocks
```

* Run ```codeblocks``` and open the source you created within Projucer

Codeblocks doesn't seem to like selecting Clang, so let's install GNU
```bash
sudo apt install g++
```

Packages
```
sudo apt-get -y install libasound2-dev
sudo apt-get -y install libfreetype6-dev
sudo apt-get -y install libxinerama-dev
sudo apt-get -y install libcurl4-gnutls-dev
sudo apt-get -y install libx11-dev
sudo apt-get -y install libxrandr-dev
sudo apt-get -y install libxcursor-dev
sudo apt-get -y install libgtk-3-dev
sudo apt-get -y install webkit2gtk-4.0
```
