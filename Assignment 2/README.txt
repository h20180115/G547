Block Device Driver
>Download the main.c partition.h and Makefile

>Go to the directory in which code is downloaded and give the command $ make all

>insert the module using sudo insmod main.ko

>check if module is loaded using lsmod command

>type the command sudo su

>Check the partition info using the command fdisk -l /dev/mydor

>we have created 2 logical partitions

>Take root access using sudo -s command 

>to write into disk use cat > /dev/mydor ,type something & press enter
to read back from the disk on command line use command xxd /dev/mydor| less

>for checking MBR use the command sudo hd -n 512 /dev/mydor


>remove the module using sudo rmmod main.ko



