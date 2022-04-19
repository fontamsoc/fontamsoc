FPGA Linux-enabled SoC supporting Wishbone4 and AXI4-Lite peripherals.

CPU implements following features:
- Instruction & Data Caches, n-way configurable.
- Pipelined Hardware Multiplication & Division.
- MMU (Memory Management Unit) with Hardware Filled TLB (Translation Lookaside Buffer) n-way configurable.

SOC includes following peripherals:
- GPIO (General Purpose Input/Output).
- DMA (Direct Memory Access).
- Interrupt controller.
- SD-Card controller supporting MMC, SDSC, SDHC and SDXC Cards.
- LiteDRAM supporting DDR2 DDR3 SDRAM.
- UART.

# Quick usage guide
- Download [disk image](https://github.com/fontamsoc/pu32/releases/latest/download/pu32.img.xz), decompress and flash it to an sdcard using either `dd if=pu32-vmlinux.img of=/dev/<sdx> bs=1M oflag=sync status=progress` or [BalenaEtcher](https://www.balena.io/etcher)
- Download FPGA bitstream: [NexysA7](https://github.com/fontamsoc/pu32/raw/main/nexys4ddr.bit), [NexysVideo](https://github.com/fontamsoc/pu32/raw/main/nexysvideo.bit)
- Flash FPGA bitstream: [NexysA7](https://digilent.com/reference/learn/programmable-logic/tutorials/nexys-4-ddr-programming-guide/start), [NexysVideo](https://digilent.com/reference/learn/programmable-logic/tutorials/nexys-video-programming-guide/start)
- Connect to serial port using 115200n8

# Demo
- [Linux booting on NexysA7](https://asciinema.org/a/424616?t=21)

# Get started
- Sources and build instructions: [PU32](https://github.com/fontamsoc/pu32)
- [Documentation](https://github.com/fontamsoc/docs)
