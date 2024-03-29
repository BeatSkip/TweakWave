# TweakWave
the goal is an open source optical spectrum analyzer with enough
performance to tune my DS-DBR fiber-optic lasers

### Contributors

-   Beatskip

### LSA

To simplify the process, the project will repurpose the internals of an
IST-REES E201 Laser spectrum analyzer (see project image). All original
electronics from the E200 Laser spectrum analyzer will be replaced by
new modern electronics to maximize performance.

### Tasks

-   \[x\] Project and documentation setup
-   \[ \] High Level Design
-   \[ \] Initial component selection
-   \[ \] PCB Design
-   \[ \] Mechanical design

## Hardware

The \'x\' indicates a component has been selected and has been acquired.
A period indicates defined, but not acquired.

-   \[x\] Ist-Rees E201 LSA Head
-   \[x\] XME0724 Zynq 7010 Module
-   \[x\] DFB Reference Laser
-   \[ \] ADC
-   \[ \] DAC
-   \[ \] Housing
-   \[ \] Misc components

## Project

The project is split up in the these components with their required
disciplines in brackets:

-   Analyzer Head \[Mechanics\]
-   Control & Readout board \[Electronics \| FPGA \| Embedded\]
-   Interface software \[Software\]
-   Reference Laser \[Physics\]

## High Level Design {#high_level_design}

### Overview

<File:TweakWave-HLD.png%7CHardware> Layout
<File:TweakWave-System.png%7CSystem> Diagram
<File:TweakWave-mainboard-V1.0.png%7CMain> Board Diagram

### Existing hardware {#existing_hardware}

<File:IST-REES_E201LSA.jpg%7CIst-Rees> E201 LSA head
<File:microphase-xme0724-zynq-som.jpg%7CXME0724> - Zynq 7010 Module
<File:Laser> \| DFB Reference Laser

## Log

\*2022-11-12 - Project definition and setup