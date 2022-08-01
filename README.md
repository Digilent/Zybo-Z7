# Zybo Z7 Root Repository

## Zybo Z7-10 DMA Audio Demo

### Description

This branch contains sources for the Zybo Z7-10 DMA Audio Demo.

This project demonstrates how to use the Zybo Z7-10's Audio Codec and RAM to record samples of audio and play them back. The Zynq processor is used to control the data pipeline. Vivado is used to build the demo's hardware platform, and Vitis is used to program the bitstream onto the board and to build and deploy a C application.

To use this demo, the Zybo Z7-10 must be connected to a computer over MicroUSB, which must be running a serial terminal. For more information on how to set up and use a serial terminal, such as Tera Term or PuTTY, refer to [this tutorial](https://reference.digilentinc.com/learn/programmable-logic/tutorials/tera-term).

The audio demo records a 5 second sample from microphone(J6) or line in (J7) and plays it back on headphone out(J5). Recording and playback are controlled by push buttons from a usb uart serial menu as shown below.

|  Button  | Function             |
| -------- | -------------------- |
|  BTN0    |  no effect           |
|  BTN1    |  record from mic in  |
|  BTN2    |  play on hph out     |
|  BTN3    |  record from line in |

For more information on the Zybo Z7-10 DMA Audio Demo, including setup instructions, visit its [Demo Page](https://reference.digilentinc.com/reference/programmable-logic/zybo-z7/demos/dma-audio) on the Digilent Wiki.

For more information on the Zybo Z7, including other demos that may be available, see its [Resource Center](https://reference.digilentinc.com/reference/programmable-logic/zybo-z7/start) on the Digilent Wiki.

### Git Navigation Information

For instructions on how to use this repository with git, and for additional documentation on the submodule and branch structures used, please visit [Digilent FPGA Demo Git Repositories](https://reference.digilentinc.com/reference/programmable-logic/documents/git) on the Digilent Wiki. Note that use of git is not required to use this demo. Digilent recommends the use of project releases, for which instructions can be found in each demo wiki page, linked above.

To see other demos in this repository, see the master branch's [README](https://github.com/Digilent/Zybo-Z7).

Some demos do not require some submodules, in these cases, they are still provided to ease switching between demos in git. When unused, the submodule folder is largely empty, except for a readme containing only the heading "Root commit". This demo contains the following submodules:

| Submodule | Used by this demo |
|-----------|-------------------|
| HW        | Yes               |
| OS        | No                |
| SW        | Yes               |

This demo was moved into this repository during 2020.1 updates. Its history prior to these updates can be found in its old repository, linked below:
* https://github.com/Digilent/Zybo-Z7-10-DMA

### Requirements

The following are required for use of this demo. For more information on how to get any hardware or software you may be missing, see the Demo Page, linked above.

* **Zybo Z7-10**
* **Vivado and Vitis 2022.1**
* **Serial Terminal Emulator**
* **MicroUSB Cable**
* **Audio cables, Microphone, Speakers**
