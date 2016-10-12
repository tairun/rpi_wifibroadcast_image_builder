# RaspberryPi **wifibroadcast** Image Builder
This repository aims to provide an alternative and easier way to build the wifibroadcast RaspberryPi sdcard images.
See the following links for the original project:
* https://befinitiv.wordpress.com/wifibroadcast-analog-like-transmission-of-live-video-data/
* https://befinitiv.wordpress.com/wifibroadcast-analog-like-transmission-of-live-video-data/wifibroadcast-fpv-manual-setup/
* https://bitbucket.org/befi/rpi_wifibroadcast_image_builder
* https://github.com/befinitiv/rpi_wifibroadcast_image_builder/releases
* https://bitbucket.org/befi/wifibroadcast

## Goals /Todos
1. Migrate build machine to vagrant
2. Add support for other network cards (injection and power level kernel patches)
3. Craete RAMDISK image for faster performance (https://buildroot.org/)
https://github.com/SamuelBrucksch/buildroot-for-wifibroadcast
4. Buildhooks for automated image generation
5. Add GitLFS

## Original content of README by befinitiv
```
This repository contains scripts for the automatic creation of wifibroadcast RX and TX images.
The following assumes Ubuntu 14.04.
Prerequisites: sudo apt-get install qemu qemu-user-static binfmt-support
To build the images run: ./build_images.sh
After the scripts are done, you find an RX and TX image under data/.
```

## License
MIT