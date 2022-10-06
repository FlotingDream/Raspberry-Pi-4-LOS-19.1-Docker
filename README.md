# Raspberry-Pi-4-LOS-19.1-Docker
Kernel -- Full natively support the Docker in Raspberry Pi 4​ LOS 19.1 Android.


Hi! This is my kernel patch for **full natively support the docker**. PI 4 LOS 19.1 Android. Tested in 4G , 8G worked fine.

based on
LineageOS 19 (Android 12L)​
for Raspberry Pi 4​
September 23, 2022

common-android12-5.10-lts

can find in 
**https://androidfilehost.com/?w=files&flid=329390**

**lineage-19.1-20220923-UNOFFICIAL-KonstaKANG-rpi4.zip**



**=====Usage=====**



1.unzip and replace the files in your sdcard **/boot/...**

2.reboot and install **termux**

3.in termux run **pkg install root-repo && pkg install docker**

4.give the **--net=host --dns=8.8.8.8** flags when running a container.

5.**enjoy it!**



thx: https://gist.github.com/FreddieOliveira/efe850df7ff3951cb62d74bd770dce27

thx: https://konstakang.com/devices/rpi4/LineageOS19/
