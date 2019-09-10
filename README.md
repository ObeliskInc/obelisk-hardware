# Obelisk Hardware Files

## Overview
This repository contains the enclosure, control board, and hashing board designs of both generations of Obelisk miners. The files herein give
you the ability to manufacture Obelisk enclosures or PCBs. You are welcome to modify the designs and use them in your own projects.

This repository does not contain the designs for SC1 or DCR1 ASICs, which are proprietary IP.

*NOTE: This document is not yet complete.  We expect to add more information over the following weeks.*

## File Organization

The files in this repository are split into two sections:

* Generation 1 Mining Hardware
* Generation 2 Mining Hardware

Each section includes **Mechanical** and **Electrical** designs.

Mechanical designs include the following file types:

* PDF files: these are typically engineering drawings, which are helpful to manufacturers
* EASM files: these are SolidWorks eDrawings files, which provide a view of the entire assembly that cannot be edited
* DXF files: these are 2-dimentional drawings files, which are typically used for components that are cut (and not bent)
* SLDPRT files: these are SolidWorks part files, which can easily be modified
* SLDASM files: these are SolidWorks assembly files, which references individual SLDPRT files and can be easily modified

To modify our mechanical designs, you can make changes to SLDPRT files in SolidWorks, create a new SLDASM assembly, and generate PDF drawings as needed.
There are numerous tools to convert SolidWorks files to other file formats, some of which can be used by open source CAD editors.

## Generation 1 Mining Hardware

Our first generation of miners, these are also referred to as "Batch 1" hardware. These Gen 1 miners use 120mm fans and resemble
a more traditional ASIC miner form factor.

The Gen 1 enclosure consists of four individual pieces of powder-coated sheet metal, as well as plastic PCB guides and sheet metal airflow guides.

The Gen 1 control board utilizes a SOM (system on module) made by Microchip, and its size is intended to serve as a bottom rest for the hashing boards.

The Gen 1 hashing board consists of 15 ASICs powered in series, each with individual heatsinks.

## Generation 2 Mining hardware

Our second generation of miners, these are also referred to as "Batch 2" or "slim" hardware. These Gen 2 miners use 60mm fans and are approximately half
the width of a traditional ASIC miner. Internally, we referred to Gen 2 miners as the "slimmy" design.

The Gen 2 enclosure consists of five individual pieces of powder-coated sheet metal, and utilizes several standoffs in lieu of screws for easy dissasembly.

The Gen 2 control board is extremely compact and utilizes a microcontroller made by STMicroelectronics.

The Gen 2 hashing board consists of 32 ASICs powered in series, with a large uniform heatsink for better resilience and easier install.