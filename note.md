## Build
```
make ARCH=arm CROSS_COMPILE=/media/work/EXT4/_work_/f1c100s/f1c100s-tools/gcc-linaro-7.2.1-2017.11-x86_64_arm-linux-gnueabi/bin/arm-linux-gnueabi-
```

## Copy to NFS root
```
sudo cp *.ko /media/work/EXT4/_work_/f1c100s/f1c100s-rootfs/buildroot-2017.08/output/images/lib/modules/4.15.0-next-20180202-licheepi-nano+ -avi
```
