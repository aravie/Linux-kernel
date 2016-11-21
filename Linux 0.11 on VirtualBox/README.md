# Linux Kernel 0.11 on VirtualBox

There are many documents about Linux 0.11 running on Bochs, Qemu. But I see no one doing it on VirtualBox. It can be simple and straightforward, though still took me some time to get it right.

The purpose is to compile the Linux 0.11 source code and get it run under VirtualBox. It contains 2 files: boot.img (on floppy) and root.img (on HDD) to have Linux 0.11 running on VirtualBox.

## Environment
Ubuntu 14.04

## Prerequisite
Bochs 2.6.8 - http://bochs.sourceforge.net
linux_devel_040329.zip - Linux 0.11 source code from http://www.oldlinux.org
VirtualBox 5.0.16 - https://www.virtualbox.org

## Preparation on host computer (Ubuntu)
- download & install Bochs
- download linux_devel_040329.zip and unzip
