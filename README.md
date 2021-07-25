Linux-enabled SoC supporting Wishbone4 and AXI4-Lite peripherals.

CPU implements following features:
- Instruction & Data Caches.
- Pipelined Hardware Multiplication & Division.
- MMU (Memory Management Unit) with Hardware Filled TLB (Translation Lookaside Buffer).

SOC includes following peripherals:
- SD-Card controller supporting MMC, SDSC, SDHC and SDXC Cards.
- LiteDRAM supporting DDR2 DDR3 SDRAM.
- UART controller.

# Quick usage guide
- Download [disk image](https://github.com/fontamsoc/pu32/releases/download/pu32.20210708/pu32-vmlinux.img.xz), decompress and flash it to an sdcard using either `dd if=pu32-vmlinux.img of=/dev/<sdx> bs=1M oflag=sync status=progress` or [BalenaEtcher](https://www.balena.io/etcher)
- Download FPGA bitstream (ie: [NexysA7](https://github.com/fontamsoc/pu32/blob/main/nexys4ddr.bit))
- Flash FPGA bitstream (ie: [NexysA7](https://reference.digilentinc.com/programmable-logic/nexys-a7/reference-manual#usb_host_and_micro_sd_programming))
- Connect to serial port using 115200n8

# Demo
- [Linux booting on NexysA7](https://asciinema.org/a/424616?t=10)

# Get started
- Sources and build instructions: [PU32](https://github.com/fontamsoc/pu32)
- [Documentation](https://github.com/fontamsoc/docs)
