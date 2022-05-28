# debug

sudo apt-get install p7zip-full

7z x vmlinux_x86_64.7z

qemu-system-x86_64 -kernel bzImage_x86_64 -initrd ./ramdisk.img.gz -nographic -append "console=ttyS0" -s -S

gdb vmlinux_x86_64




# busybox version
alpine-minirootfs-3.12.0-x86_64.tar.gz   

https://dl-cdn.alpinelinux.org/alpine/v3.12/releases/x86_64/


