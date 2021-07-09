# Quick usage guide
- Download [disk image](https://github.com/fontamsoc/pu32/releases/download/pu32.20210708/pu32-vmlinux.img.xz), decompress and flash it to an sdcard using either `dd if=pu32-vmlinux.img of=/dev/<sdx> bs=1M oflag=sync status=progress` or [BalenaEtcher](https://www.balena.io/etcher)
- Flash FPGA bitstream (ie: [NexysA7](https://reference.digilentinc.com/programmable-logic/nexys-a7/reference-manual#usb_host_and_micro_sd_programming))
- Connect to serial port using 115200n8

[![asciicast](https://asciinema.org/a/424616.svg)](https://asciinema.org/a/424616?t=10)
