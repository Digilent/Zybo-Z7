# Zybo Z7 Root Repository

## Zybo Z7-20 XADC Demo

### Description

This branch contains sources for the Zybo Z7-20 XADC Demo.

This project is a Vivado demo using the Zybo Z7-20 analog-to-digital converter ciruitry and LEDs, written in Verilog. When programmed onto the board, voltage levels between 0 and 1 Volt are read off of the JXADC header. Each XADC channel will control the brightness of an LED as shown in the following table.

For more information on the Zybo Z7-20 XADC Demo, including setup instructions, visit its [Demo Page](https://reference.digilentinc.com/reference/programmable-logic/zybo-z7/demos/xadc) on the Digilent Wiki.

For more information on the Zybo Z7, including other demos that may be available, see its [Resource Center](https://reference.digilentinc.com/reference/programmable-logic/zybo-z7/start) on the Digilent Wiki.

### Git Navigation Information

For instructions on how to use this repository with git, and for additional documentation on the submodule and branch structures used, please visit [Digilent FPGA Demo Git Repositories](https://reference.digilentinc.com/reference/programmable-logic/documents/git) on the Digilent Wiki. Note that use of git is not required to use this demo. Digilent recommends the use of project releases, for which instructions can be found in each demo wiki page, linked above.

To see other demos in this repository, see the master branch's [README](https://github.com/Digilent/Zybo-Z7).

Some demos do not require some submodules, in these cases, they are still provided to ease switching between demos in git. When unused, the submodule folder is largely empty, except for a readme containing only the heading "Root commit". This demo contains the following submodules:

| Submodule | Used by this demo |
|-----------|-------------------|
| HW        | Yes         |
| OS        | No         |
| SW        | No         |

This demo was moved into this repository during 2020.1 updates. Its history prior to these updates can be found in its old repository, linked below:
* https://github.com/Digilent/Zybo-Z7-20-XADC/

### Requirements

The following are required for use of this demo. For more information on how to get any hardware or software you may be missing, see the Demo Page, linked above.

* Zybo Z7-20
* Vivado 2022.1 Installation
* MicroUSB Cable
* Wires and a Circuit to Measure
