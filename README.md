A quick guide on how to install a MHS 3.5 inch LCD on a Raspberry Pi running 64bit OS (namely Raspbian). This is cloned and cobbled together from https://github.com/tux1c/wavesharelcd-64bit-rpi (who deserves all the credit) and is tested on a RPi 4 with a fresh install of Raspbian 64 bit beta from here https://www.raspberrypi.org/forums/viewtopic.php?t=275370

# Installation
`git clone https://github.com/InfoSecREDD/MHS35-lcd-64bit-rpi.git`

`cd MHS35-lcd-64bit-rpi`

`chmod +x install.sh`

`sudo bash install.sh`

# Troubleshooting
## White screen on boot (raspberry pi boots)
make sure `dtoverlay=vc4-fkms-v3d` is **NOT** present / commented out in `/boot/config.txt`

