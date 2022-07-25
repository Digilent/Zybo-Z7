# Zybo-Z7 Root Repository

This repository contains all demo projects for Zybo-Z7-10 and Zybo-Z7-20.

For more information about the Zybo-Z7 visit its [Resource Center](https://digilent.com/reference/programmable-logic/zybo-z7/start?redirect=1) on the Digilent Wiki.

Each demo contained in this repository is documented on the Digilent Wiki. Depending on your Zybo-Z7 version (10 or 20) you need to navigate to the proper branch (10/... or 20/...).

Useful links are provided in the table below.

|Wiki link|Demo Master Branch|Submodules Used|
|---------|------------------|---------------|
|[Zybo-Z7 DMA Audio Demo](https://digilent.com/reference/programmable-logic/zybo-z7/demos/dma-audio)|10/DMA/master, 20/DMA/master|HW, SW|
|[Zybo-Z7 HDMI I/O Demo](https://digilent.com/reference/programmable-logic/zybo-z7/demos/hdmi)|10/HDMI/master, 20/HDMI/master|HW, SW|
|[Zybo-Z7 Pmod VGA Demo](https://digilent.com/reference/programmable-logic/zybo-z7/demos/pmod-vga)|10/Pmod-VGA/master, 20/Pmod-VGA/master|HW|
|[Zybo-Z7 XADC Demo](https://digilent.com/reference/programmable-logic/zybo-z7/demos/xadc)|10/XADC/master, 20/XADC/master|HW|
|[Zybo-Z7-20 Pcam 5C Demo](https://digilent.com/reference/learn/programmable-logic/tutorials/zybo-z7-pcam-5c-demo/start)|20/Pcam-5C/master|HW, SW|

## Repository Description

This repository is designed to offer a unified and comprehensive approach to all of the aspects of the demos that we provide for the Zybo-Z7, across multiple tools. By cloning this repo recursively you will receive the repositories for Vivado projects (HW), and Vitis workspaces (SW). Each submodule may have its own submodule dependencies which will also be pulled when cloning. An important aspect of this structure is the fact that the SW heavily depends on hardware hand-off files from the HW repository.

This repository also provides releases containing project and image files used by the various tools involved. Releases provide files that are directly usable, without requiring the use git or any scripting systems. Documentation of each demo, as well as instructions for using their releases, can be found by visiting the corresponding pages on the Digilent Wiki, links below. All releases in this repository can be found in this repository's [releases page](https://github.com/Digilent/Zybo-Z7/releases), however, use of the wiki pages to find specific well-tested releases is advised.

For instructions on how to use this repository with git, and for additional documentation on the submodule and branch structures used, please visit [Digilent FPGA Demo Git Repositories](https://digilent.com/reference/programmable-logic/documents/git?redirect=1) on the Digilent Wiki. Note that use of git is not required to use this demo. Digilent recommends the use of project releases, for which instructions can be found in each demo wiki page, linked in the table of demos, above.

Demos were moved into this repository during 2020.1 updates. History of these demos prior to these updates can be found in their old repositories, linked below:

- https://github.com/Digilent/Zybo-Z7-10-DMA
- https://github.com/Digilent/Zybo-Z7-20-DMA
- https://github.com/Digilent/Zybo-Z7-10-HDMI
- https://github.com/Digilent/Zybo-Z7-20-HDMI
- https://github.com/Digilent/Zybo-Z7-10-Pmod-VGA
- https://github.com/Digilent/Zybo-Z7-20-Pmod-VGA
- https://github.com/Digilent/Zybo-Z7-10-XADC
- https://github.com/Digilent/Zybo-Z7-20-XADC
- https://github.com/Digilent/Zybo-Z7-20-pcam-5c

