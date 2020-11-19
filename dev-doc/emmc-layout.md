Partition layout of EMMC
===


```
partition layer of EMMC
---------------------------------------------------------------------
|   |     |   |        |     |       |    |    |        |           |
|   | SPL |   | U-BOOT | Env |  ~~~  | P1 | P2 |   P3   |    P4     |
|   |     |   |        |     |       |    |    |        |           |
---------------------------------------------------------------------
=====================================================================
SPL:	MLO,			offset 128KB,	size: 128KB
U-BOOT: u-boot.img		offset 384KB,	size: 256KB
Env:    u-boot env. variables   offset 1MB,     size: 128KB+128KB
P1: 	Reserved partition	offset 4MB, 	size: 64MB
P2: 	Boot partition		offset 68MB, 	size: 64MB
P3:	Root filesystem		offset 132MB,	size: 2GB
P4:	User Data		offset 2180MB,	size: over 5GB
=====================================================================

```

we support root filesystem on overlayfs now.
 
* P1 for backup boot partitions
* P2 is boot partition, bootloader from this partition read kernel/fdt/initrd
* P3 is overlayfs lowdir
* P4 is overlayfs upperdir
