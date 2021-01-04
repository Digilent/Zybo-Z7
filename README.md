# Zybo Z7 Root Repository

## Zybo Z7-20 Pcam-5C Demo

### Description

This branch contains sources for the Zybo Z7-20 Pcam-5C Demo.

The Zybo Z7 Pcam 5C project demonstrates the usage of the Pcam 5C as a video source by forwarding the streaming image data out to the HDMI TX port. Video data streams in through the Pcam port and out through the HDMI source (TX) port. A UART interface is available to configure the image sensor and additional post processing IP Cores.

For more information on the Zybo Z7-20 Pcam-5C Demo, including setup instructions, visit its [Demo Page](https://reference.digilentinc.com/reference/programmable-logic/zybo-z7/demos/pcam-5c) on the Digilent Wiki.

For more information on the Zybo-Z7, including other demos that may be available, see its [Resource Center](https://reference.digilentinc.com/reference/programmable-logic/Zybo-Z7/start) on the Digilent Wiki.

### Git Navigation Information

For instructions on how to use this repository with git, and for additional documentation on the submodule and branch structures used, please visit [Digilent FPGA Demo Git Repositories](https://reference.digilentinc.com/reference/programmable-logic/documents/git) on the Digilent Wiki. Note that use of git is not required to use this demo. Digilent recommends the use of project releases, for which instructions can be found in each demo wiki page, linked above.

To see other demos in this repository, see the master branch's [README](https://github.com/Digilent/Zybo-Z7).

Some demos do not require some submodules, in these cases, they are still provided to ease switching between demos in git. When unused, the submodule folder is largely empty, except for a readme containing only the heading "Root commit". This demo contains the following submodules:

| Submodule | Used by this demo |
|-----------|-------------------|
| HW        | Yes         |
| OS        | No         |
| SW        | Yes      |

This demo was moved into this repository during 2020.1 updates. Its history prior to these updates can be found in its old repository, linked below:
* https://github.com/Digilent/Zybo-Z7-20-pcam-5c

### Requirements

The following are required for use of this demo. For more information on how to get any hardware or software you may be missing, see the Demo Page, linked above.

* Zybo Z7 with a MicroUSB Programming Cable and External Power Supply
* 1 Pcam 5C Assembly
* Vivado and Vitis installations compatible with the latest release of this demo
* Serial Terminal application to receive messages printed by the demo
* 1 HDMI Type A to Type A or HDMI Type A to DVI-D cable
* HDMI or DVI monitor
