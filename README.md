Hello...

This repository contains sample mobile applications which can be used to explore different tools and frameworks. 

I will be adding new apps as and when I found them. Keep watching this repository.

Tipcs and Tricks

1. iOS simulators not visible in katalon studio

Your xcode-select command output looks like it might cause you problems. Can you try running the command:

sudo xcode-select -s /Applications/Xcode.app/Contents/Developer

Refer this link - https://forum.katalon.com/t/ios-simulators-not-visible-in-katalon-studio/13571/3

2. iOS Applications keeps on launching and closing immediately 

To unstall and install Appium stable and compatable version with Katalon version - 6.3.3 

sudo npm install -g appium@1.8.2-beta --unsafe-perm=true --allow-root
