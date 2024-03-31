Course - Advanced Physical Design Using OpenLANE offered by VSDIAT
BY-VIGNESH

Contents:-

Day 1: How to Talk to Computers

Introduction to QFN - 48 package, chip, pads, core, die and IPs

Introduction to RISC V

From Software Applications to Hardware

SoC Design and OpenLANE

Introduction to Components of Opensource Digital ASIC Design

Simplified RTL to GDS flow

Introduction to OpenLANE and Strive Chipsets

Introduction to OpenLANE detailed ASIC Design Flow

Get Familiar to Opensource EDA tools

OpenLANE Directory Structure in Detail

Design Preparation Step

Review Files After Design Prep and Run Synthesis

Steps to Characterise Synthesis Results

Screenshots for labs and theory done-

https://github.com/Vigneshr2106/ADVANCED-PHYSICAL-DESIGN-USING-OPENLANE-BY-VIGNESH/issues/1#issue-2216571305


Day 2: Good vs Bad Floorplan and Introduction to Library Cells

Chip Floor Planning Considerations

Utilisation Factor and Aspect Ratio

Concept of Pre-Placed Cells

De-Coupling Capacitors

Power Planning

Pin Placement and Logical Cell Placement Blockage

Steps to Run Floorplan Using OpenLANE

Review Floorplan Files and Steps to Review Floorplan

Review Floorplan Layout in Magic

Library Binding and Placement

Netlist Binding and Initial Place Design

Optimise Placement Using Estimated Wire-Length and Capacitance

Final Placement Optimization

Need for Libraries and Characterisation

Congestion Aware Placement Using RePLACE

Cell Design and Characterisation Flows

Inputs for Cell Design Flow

Circuit Design Step

Layout Design Step

Typical Characterisation Flow

General Timing Characterisation Parameters

Timing Threshhold Definitions

Propogation Delay and Transition Time

DAY 3: Design Library Cell Using Magic Layout and NGSPICE characterisation

Labs for CMOS Inverter NGSPICE Simulations

IO Placer Revision

SPICE Deck Creation For CMOS Inverter

SPICE Simulation Lab for CMOS Inverter

Switching Threshhold Vm

Static and Dynamic Simulation of CMOS Inverter

Lab Steps to GitClone VSDSTD Cell Design

Inception of Layout Â CMOS Fabrication Process

Create Active Regions

Formation of N and P well

Formation of Gate Terminal

Lightly Doped Drain [LDD] Formation

Source Â Drain Formation

Local Interconnect Formation

Higher Level Metal Formation

Lab Introduction to SKY130 Basic Layers Layout and LEF using Inverter

Lab Steps to Create STD Cell Layout and Extract SPICE Netlist

SKY130 Tech File Labs

Lab Steps To Create Final SPICE deck using SKY130 tech

Lab Steps to Characterise Inverter using SKY130 Model Files

Lab Introduction to SKY130 PDKs And Steps to Download Labs

Lab Introduction to Magic Tool Options and DRC Rules

Lab Introduction to Magic and Steps to Load SKY130 Tech Rules

Lab Excercise to Fix poly.9 error in SKY130 Tech-File

Lab Excercise to Implement Poly-Resistor Spacing to Diff and Tap


DAY 4 : Pre-Layout Timing Analysis and Importance of Good Clock Tree

Timing Modelling Using Delay Tables

Lab Steps To Convert Grid Information Into Track Information

Lab Steps to Convert Magic Layout to STD Cell LEF

Introduction of Timing libs and Steps To Include New Cell in Synthesis

Delay Tables

Lab Steps To Configure Synthesis Settings to Fix Slack and Include VSDINV

Timing Analysis With Ideal Clocks Using Open STA

Setup Timing Analysis And Introduction to Flip-Flop Setup Time

Introduction to Clock Jitter and Uncertainty

Lab Steps to Configure OpenSTA for Post-Synth Timings Analysis

Lab Steps to Optimize Synthesis to Reduce Setup Violations

Lab Steps to do Basic Timing ECO

Clock Tree Synthesis TritonCTS and Signal Integrity

Clock Tree Routing and Buffering Using H-Tree Algorithm

Crosswalk and Clock Net Shielding

Lab Steps to run CTS using TritonCTS

Lab Steps to Verify CTS Runs

Timing Analysis With Real Clocks Using Open STA

Setup Timing Analysis Using Real Clocks

Lab Steps to Analyse Timing With Real Clocks Using OpenSTA

Lab Steps to Excecute OpenSTA With Right Timing Libraries and CTS Assignment

Lab Steps to Observe Impact of Bigger CTS Buffers On Setup And Hold Timing

DAY 5: Final Steps For RTL2GDS Using TritonRoute and OpenSTA

Routing and Design Check

Introduction to Maze Routing and Lee's Algorithm

Lee's Algorithm Conclusion

Design Rule Check

Power Distribution Network and Routing

Lab Steps To Build Power Distribution Network

Lab Steps From Power Straps To STD Cell Power

Basics of Global and Detail Routing and Configure TritonRoute

TritonRoute Features

TritonRoute Feature 1 - Honors Pre-processed Route Guides

TritonRoute Feature 2 & 3 - Inter-Guide Connectivity and Intra & Inter Layer Routing

TritonRoute Method To Handle Connectivity

Routing Topology Algorithm and Final Files List Post Route
