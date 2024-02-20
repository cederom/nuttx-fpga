# Apache NuttX RTOS on FPGA

This repository contains information and reference designs for running
Apache NuttX RTOS on FPGA devices. Only Open-Source tools are considered.
When ready this repository should be integrated similar way to `nuttx-apps`.

# Software

Open source toolchain for AMD Xilinx devices: [openXC7](https://github.com/openXC7)  
For other devices, particularly Lattice ECP5: [OSS CAD Suite](https://github.com/YosysHQ/oss-cad-suite-build)

# Hardware

## Lattice


* EPC5: $11.50. Includes SDRAM & Ethernet. [Colorlight N6](https://www.ledcontrollercard.com/english/colorlight-n6-led-mini-receiving-card.html)
* ECP5: $18.27 [Colorlight 5A-7B](https://es.aliexpress.com/item/1005003580229862.html), see [here](https://tomverbeure.github.io/2021/01/22/The-Colorlight-i5-as-FPGA-development-board.html) for usage

## AMD Xilinx

* Zynq 7010: $16 [EBAZ4205](https://es.aliexpress.com/item/1005004530722687.html)
* Spartan 7: $39.50 [Spartan Edge Accelerator Board (Seeed Studio)](https://wiki.seeedstudio.com/Spartan-Edge-Accelerator-Board).
* Spartan 6: $35.17 [QMTech Spartan-6](https://www.satistronics.com/shop/181172-xilinx-fpga-spartan6-spartan-6-core-board-xc6slx16-ddr3-256mb-5522)

# Examples

Using Colorlight boards: https://tomverbeure.github.io/2021/01/22/The-Colorlight-i5-as-FPGA-development-board.html

# References

* Apache NuttX RTOS: [website](https://nuttx.apache.org) / [github](https://github.com/apache/nuttx).
