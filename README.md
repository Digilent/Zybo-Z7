# Zybo Z7 Root Repository

## Zybo Z7-20 Pmod VGA Demo

### Description

This branch contains sources for the Zybo Z7-20 Pmod VGA Demo.

This project is a Vivado demo using the Zybo Z7-20's, Pmod Ports and the Pmod VGA written in VHDL.
The Pmod VGA is controlled by the Zybo Z7-20 through Pmod ports JC and JD.
When programmed onto the board, a bouncing box and many test pattern bars are displayed on a connected VGA monitor.
The screen resolution is configurable through HDL code.

For more information on the Zybo Z7-20 Pmod VGA Demo, including setup instructions, visit its [Demo Page](https://reference.digilentinc.com/reference/programmable-logic/zybo-z7/demos/pmod-vga) on the Digilent Wiki.

For more information on the Zybo Z7, including other demos that may be available, see its [Resource Center](https://reference.digilentinc.com/reference/programmable-logic/zybo-z7/start) on the Digilent Wiki.

### Git Navigation Information

For instructions on how to use this repository with git, and for additional documentation on the submodule and branch structures used, please visit [Digilent FPGA Demo Git Repositories](https://reference.digilentinc.com/reference/programmable-logic/documents/git) on the Digilent Wiki. Note that use of git is not required to use this demo. Digilent recommends the use of project releases, for which instructions can be found in each demo wiki page, linked above.

To see other demos in this repository, see the master branch's [README](https://github.com/Digilent/Zybo-Z7).

Some demos do not require some submodules, in these cases, they are still provided to ease switching between demos in git. When unused, the submodule folder is largely empty, except for a readme containing only the heading "Root commit". This demo contains the following submodules:

| Submodule | Used by this demo |
|-----------|-------------------|
| HW        | Yes          |
| OS        | No         |
| SW        | No         |

This demo was moved into this repository during 2020.1 updates. Its history prior to these updates can be found in its old repository, linked below:
* https://github.com/Digilent/Zybo-Z7-20-Pmod-VGA

### Requirements

The following are required for use of this demo. For more information on how to get any hardware or software you may be missing, see the Demo Page, linked above.

* Zybo Z7-20
* Pmod VGA
* Vivado 2021.1 Installation
* MicroUSB Cable
* VGA Monitor
* VGA Cable
