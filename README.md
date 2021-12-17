# Zybo Z7 Root Repository

## Zybo Z7-20 HDMI Demo

### Description

This branch contains sources for the Zybo Z7-20 HDMI Demo.

This project demonstrates how to use the HDMI Sink and HDMI Source with the ZYNQ processor. Vivado is used to build the demo's hardware platform, and Vitis is used to program the bitstream onto the board and to build and deploy a C application. Video data streams in through the HDMI in port and out through the HDMI out port. A UART interface is available to configure what is output through HDMI. The configuring options are shown in the table below.

Since the demo uses the USB-UART bridge to configure the HDMI Display, the Zybo Z7-20 must be connected to a computer over MicroUSB, which must be running a serial terminal. For more information on how to set up and use a serial terminal, such as Tera Term or PuTTY, refer to [this tutorial](https://reference.digilentinc.com/learn/programmable-logic/tutorials/tera-term).

| Option    | Function                                                                                                                 |
| --------- | ------------------------------------------------------------------------------------------------------------------------ |
| 1         | Change the resolution of the HDMI output to the monitor.                                                                 |
| 2         | Changes the frame buffer to display on the HDMI monitor.                                                                 |
| 3/4       | Store one of two test patterns in the chosen video frame buffer.                                                         |
| 5         | Start/Stop streaming video data from HDMI to the chosen video frame buffer.                                              |
| 6         | Change the video frame buffer that HDMI data is streamed into.                                                           |
| 7         | Invert and store the current video frame into the next video frame buffer and display it.                                |
| 8         | Scale the current video frame to the display resolution, store it into the next video frame buffer, and then display it. |

For more information on the Zybo Z7-20 HDMI Demo, including setup instructions, visit its [Demo Page](https://reference.digilentinc.com/reference/programmable-logic/zybo-z7/demos/hdmi) on the Digilent Wiki.

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
* https://github.com/Digilent/Zybo-Z7-20-HDMI

### Requirements

The following are required for use of this demo. For more information on how to get any hardware or software you may be missing, see the Demo Page, linked above.

* **Zybo Z7-20**
* **Vivado and Vitis 2020.1 Installations**
* **Serial Terminal Emulator Application**
* **MicroUSB Cable**
* **2 HDMI Cables**
* **HDMI capable Monitor/TV**
