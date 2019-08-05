IDEA: 
Like Klipper, offload computations to the PC device and allow instructions to be fed directly to the printer. 

Pros:
 - As steppers become more functional and more fine grained - better slicing needs better computational time
 - Current 3d printer motherboards are limited in CPU and memory boards excluding operations of intensive calculations and JIT coding 
 - Treat a 3D printer like any other networked paper printer
 
Cons
 - Will need to rebuild firmware from ground up
 - Need to perhaps change the idea of 3d printer motherbards to become "less intelligent" and more rote focused
 - New UI and UX to be considered


# Marlin 3D Printer Firmware
<img align="right" src="../../raw/1.1.x/buildroot/share/pixmaps/logo/marlin-250.png" />

Marlin is the world's most popular open source firmware for Replicating Rapid Prototyper (RepRap) machines, commonly referred to as "3D printers." Marlin Firmware is highly efficient, running even on modest 16MHz embedded AVR processors. While Marlin 1.1 only supports ATmega AVR (Arduino, etc.) and AT90USB (Teensy++ 2.0), [Marlin 2.0](https://github.com/MarlinFirmware/Marlin/tree/bugfix-2.0.x) also adds support for several ARM processors, including the SAM3X8E (Arduino Due), NXP LPC1768/LPC1769 ARM Cortex-M3 (Re-Arm, MKS SBASE, Smoothieboard), and ARM Cortex-M4 (Teensy 3.5/3.6, STM32F1/4/7).

A monumental amount of talent and effort goes into Marlin production, and thanks are due to many volunteers around the world. We work closely with the community, contributors, vendors, host and library developers, etc. to improve the quality, configurability, and compatibility of Marlin Firmware with a [huge variety](http://marlinfw.org/docs/configuration/configuration.html#motherboard) of boards. For the final 1.1 release we focused on code quality, performance, stability, and overall user experience. Several new features were added, many of which require no extra hardware.

