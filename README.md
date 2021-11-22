# References used on this README:
# (*anything*, *something*): Use one of the options with the parentesis. Example: boot_*ibec*-*bypass*-*S5L8940_4S*.bootz0ne
# boot_(*ramdisk, iBec, iBoot, kernelcache, devicetree*)_(*put your ramdisk name*)_(*device*).bootz0ne : the file used for searching the files, it contains a set of one or more commands for the variable BOOTZONE_(*ramdisk*, *ibec*, *iBSS*, *iBoot*, etc) Mainy using a *set* instruction.
Example: *set BOOTZONE_ramdisk=%~dp0\ramdisks\icloudbypass\iPad2_4\ramdisk*
# bootz0ne-store
Bootz0ne ramdisk loader's ramdisk store.
# How I can download the ramdisks?
you can download the ramdisks on the releases tagged 
# Is there a icloud bypass?
Yes you can use the bypass ramdisk method on A5 Devices (only if you have arduino uno & USB Host Shield 2.0).
# How I can use ramdisks?
Download the files and copy them to bootz0ne and link with the file boot_(*ramdisk, iBec, iBoot, kernelcache, devicetree*)_(*put your ramdisk name*)_(*device*).bootz0ne
# 

