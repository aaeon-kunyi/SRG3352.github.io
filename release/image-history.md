Release History
===
there for SRG-3352/SRG-3352C release history

### Nov. 25 2020 -- public 1.0-beta release
filename: [srg3352c-buster_1.0-beta_2020-11-25.zip](https://github.com/aaeon-kunyi/meta-srg52x/releases/download/v1.0-beta/srg3352c-buster_1.0-beta_2020-11-25.zip)

build from https://github.com/aaeon-kunyi/meta-srg52x/commit/129544125cfedd4911cfc1eb2414066889cd5cd2

### change log:
	* remove root password
	* add user account aaeon for sudoer
	* implement BUILD_DATE property of /etc/os-release
	* add IMG_VARIANT_VERSION of build environment variable for VARIANT_VERSION of /etc/os-release
	* fixed some build script bugs
	* update issues/motd for user login experience
	* assign static ip setting for eth0 & eth1
		* 192.168.3.127 for eth0
		* 192.168.4.127 for eth1

##### bootloader build & information:
`
U-Boot 2019.01-SRG-3352C-2020.11 (Nov 25 2020 - 02:22:59 +0000)
`

##### kernel version:
`
Linux SRG-3352C 4.19.94-SRG52x-rt52 #1 PREEMPT RT Wed Nov 25 02:28:19 UTC 2020 armv7l GNU/Linux
`

##### os-release information (check BUILD_ID):
```
aaeon@SRG-3352C:~$ cat /etc/os-release
PRETTY_NAME="Debian GNU/Linux 10 (buster)"
NAME="Debian GNU/Linux"
VERSION_ID="10"
VERSION="10 (buster)"
VERSION_CODENAME=buster
ID=debian
HOME_URL="https://www.debian.org/"
SUPPORT_URL="https://www.debian.org/support"
BUG_REPORT_URL="https://bugs.debian.org/"
IMAGE_UUID="412c9c76-8f21-4a11-9803-9b9df58ead58"
BUILD_ID="1295441"
BUILD_DATE="2020/11/25"
VARIANT="SRG-3352x Debian Buster image"
VARIANT_VERSION="1.0-beta"

```

##### known issues:
none

---
### Nov. 20 2020 -- internal alpha release
filename: srg-3352c_buster_alpha_20201120.zip

build from https://github.com/aaeon-kunyi/meta-srg52x/commit/d5c9967ab617e8931629b84e2f66018528eb47c9

### change log:
	* implemet automount feature for micro SD and usb disk
	* update srg52_emmc_flasher.sh


##### bootloader build & information:
`
U-Boot 2019.01-SRG-3352C-2020.11 (Nov 20 2020 - 07:37:02 +0000)
`

##### kernel version:
`
Linux SRG-3352C 4.19.94-SRG52x-rt52 #1 PREEMPT RT Fri Nov 20 07:42:35 UTC 2020 armv7l GNU/Linux
`

##### os-release information (check BUILD_ID):
```
root@SRG-3352C:~# cat /etc/os-release
PRETTY_NAME="Debian GNU/Linux 10 (buster)"
NAME="Debian GNU/Linux"
VERSION_ID="10"
VERSION="10 (buster)"
VERSION_CODENAME=buster
ID=debian
HOME_URL="https://www.debian.org/"
SUPPORT_URL="https://www.debian.org/support"
BUG_REPORT_URL="https://bugs.debian.org/"
IMAGE_UUID="10f35fc7-a950-4fc4-9a38-6dc2bae3d7de"
BUILD_ID="d5c9967"
VARIANT="SRG-3352x Debian Buster image"
VARIANT_VERSION="1.0"

```

##### known issues:
none

---
### Nov. 19 2020 -- internal alpha release 
filename: srg-3352c_buster_alpha_20201119.zip

build from https://github.com/aaeon-kunyi/meta-srg52x/commit/8ea4d6f299c985fc1d79277616fef2f9b5cf1402


### change log:
	* implemet overlay to merge rootfs/data partition


##### bootloader build & information:
`
U-Boot 2019.01-SRG-3352C-2020.11 (Nov 19 2020 - 07:21:38 +0000)
`

##### kernel version:
`
Linux SRG-3352C 4.19.94-SRG52x-rt52 #1 PREEMPT RT Thu Nov 19 07:27:04 UTC 2020 armv7l GNU/Linux
`

##### os-release information (check BUILD_ID):
```
root@SRG-3352C:~# cat /etc/os-release
PRETTY_NAME="Debian GNU/Linux 10 (buster)"
NAME="Debian GNU/Linux"
VERSION_ID="10"
VERSION="10 (buster)"
VERSION_CODENAME=buster
ID=debian
HOME_URL="https://www.debian.org/"
SUPPORT_URL="https://www.debian.org/support"
BUG_REPORT_URL="https://bugs.debian.org/"
IMAGE_UUID="ad3db9c6-54a9-4902-92cd-28e6a54ffb52"
BUILD_ID="8ea4d6f"
VARIANT="SRG-3352x Debian Buster image"
VARIANT_VERSION="1.0"
```

##### known issues:
none


---
