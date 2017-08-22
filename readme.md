# Get the library
```bash
git clone https://github.com/WeAreROLI/JUCE
```

# Dependencies (Ubuntu 16)
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

# Compile the demo
```bash
cd JUCE/examples/Demo/Builds/LinuxMakefile
make -j 4
```
# Documentation
* https://www.juce.com/doc/tutorial_new_projucer_project

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

