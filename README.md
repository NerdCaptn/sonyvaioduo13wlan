# Sony Vaio Duo 13 WLAN Fix
This is the WLAN Fix for the Sony Vaio Duo 13 with Ubuntu 17.04.

# Installation
Just copy the two files into your /lib/firmware/brcm folder.
Then reboot the machine or reload the firmware with:
* modprobe -rfv brcmfmac
* modprobe -v brcmfmac

# Credits
I copied it from https://www.dropbox.com/s/8m9n4qolf76iz11/brcmfmac-sdio.zip.
