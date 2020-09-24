---
title: Harmony 3 Content Manager
nav_order: 1
has_children: false
---

# MPLAB® Harmony 3 Content Manager

MPLAB® Harmony 3 is an extension of the MPLAB® ecosystem for creating
embedded firmware solutions for Microchip 32-bit SAM and PIC microcontroller
and microprocessor devices.  Refer to the following links for more information.
 - [Microchip 32-bit MCUs](https://www.microchip.com/design-centers/32-bit)
 - [Microchip 32-bit MPUs](https://www.microchip.com/design-centers/32-bit-mpus)
 - [Microchip MPLAB® X IDE](https://www.microchip.com/mplab/mplab-x-ide)
 - [Microchip MPLAB® Harmony](https://www.microchip.com/mplab/mplab-harmony)
 - [Microchip MPLAB® Harmony Pages](https://microchip-mplab-harmony.github.io/)

This repository contains the implementation of the MPLAB® Harmony 3 Content Manager tool (MHCM). The MHCM is an easy to use development tool with a Graphical User Interface (GUI) that simplifies the manipulation of MPLAB® Harmony Content. The MHCM is available as a plugin that directly integrates with the MPLAB® X IDE or as a separate Java executable for standalone use with other development environments.

The MHCM includes a downloader tool that reads an online catalog of MPLAB Harmony 3 library packages so that the developers can select and download the libraries in which they are interested. It includes also an Application Browser allowing to copy selected application(s) to any location on your machine.

 - [Getting started with Content Manager](doc/readme.md)
 - [Release Notes](release_notes.md)

## Setup to launch Content Manager as Standalone

This repository can be downloaded and the harmony-content-manager.jar can be executed as standalone. For this, the following setup is requried.
 - Based on your operating system and Processor Architecture, download JRE 8 with FX support from the given link (https://www.azul.com/downloads/zulu-community/?&version=java-8-lts&package=jre-fx)
 - Extract the compressed jre to any location in your system and set the "PATH" variable to "<JRE_ROOT_LOCATION>/bin"
 - Go to the place where harmony-content-manager.jar is present in Command Line Interface and execute command "java -jar harmony-content-manager.jar"

## Content Summary

| File/Folder  | Description                                                   |
|--------------|---------------------------------------------------------------|
| *.jar        | Java libraries.                                               |
| harmony-content-manager.jar      | Main Java executable (run: java -jar harmony-content-manager.jar)   |
| runme.bat    | Windows shell script to run standalone MHCM GUI.              |
| runme.sh     | non-Windows shell script to run standalone MHCM GUI.          |

## Open source Libraries

Content manager uses following open sources libraries:

| Library Name                                  | Version                    | License                                                                                               |
|-----------------------------------------------|---------------------------|-------------------------------------------------------------------------------------------------------|
| [jsch-0.1.54.jar](https://mvnrepository.com/artifact/com.jcraft/jsch/0.1.54)								| 0.1.54              | Revised BSD http://www.jcraft.com/jsch/LICENSE.txt                                        |
| [jsoup-1.10.2.jar](https://mvnrepository.com/artifact/org.jsoup/jsoup/1.10.2)								| 1.10.2              | MIT License http://www.opensource.org/licenses/mit-license.php                                        |
| [org.eclipse.jgit-4.11.0.201803080745-r.jar](https://mvnrepository.com/artifact/org.eclipse.jgit/org.eclipse.jgit/4.11.0.201803080745-r)   	| 4.11.0.201803080745-r | Eclipse Distribution License (New BSD License)                                            |
| [simple-xml-2.7.1.jar](https://mvnrepository.com/artifact/org.simpleframework/simple-xml/2.7.1)                          | 2.7.1               | The Apache Software License, Version 2.0 [http://www.apache.org/licenses/LICENSE-2.0.txt](http://www.apache.org/licenses/LICENSE-2.0.txt)               |
| [slf4j-api-1.7.25.jar](https://mvnrepository.com/artifact/org.slf4j/slf4j-api/1.7.2)                         	| 1.7.25              | MIT License http://www.opensource.org/licenses/mit-license.php                            |
| [slf4j-simple-1.7.25.jar](https://mvnrepository.com/artifact/org.slf4j/slf4j-simple/1.7.25)                      	| 1.7.25              | MIT License http://www.opensource.org/licenses/mit-license.php                            |
| [snakeyaml-1.26.jar](https://mvnrepository.com/artifact/org.yaml/snakeyaml/1.26)                      	| 1.26.0              | The Apache Software License, Version 2.0 [http://www.apache.org/licenses/LICENSE-2.0.txt](http://www.apache.org/licenses/LICENSE-2.0.txt)               |
| [jfoenix-8.0.10.jar](https://mvnrepository.com/artifact/com.jfoenix/jfoenix/8.0.10)                      	| 8.0.10              | The Apache Software License, Version 2.0 [http://www.apache.org/licenses/LICENSE-2.0.txt](http://www.apache.org/licenses/LICENSE-2.0.txt)               |
____
[![License](https://img.shields.io/badge/license-Harmony%20license-orange.svg)](https://github.com/Microchip-MPLAB-Harmony/contentmanager/blob/master/mplab_harmony_license.md)
[![Latest release](https://img.shields.io/github/release/Microchip-MPLAB-Harmony/contentmanager.svg)](https://github.com/Microchip-MPLAB-Harmony/contentmanager/releases/latest)
[![Latest release date](https://img.shields.io/github/release-date/Microchip-MPLAB-Harmony/contentmanager.svg)](https://github.com/Microchip-MPLAB-Harmony/contentmanager/releases/latest)
[![Commit activity](https://img.shields.io/github/commit-activity/y/Microchip-MPLAB-Harmony/contentmanager.svg)](https://github.com/Microchip-MPLAB-Harmony/contentmanager/graphs/commit-activity)
[![Contributors](https://img.shields.io/github/contributors-anon/Microchip-MPLAB-Harmony/contentmanager.svg)]()
____

[![Follow us on Youtube](https://img.shields.io/badge/Youtube-Follow%20us%20on%20Youtube-red.svg)](https://www.youtube.com/user/MicrochipTechnology)
[![Follow us on LinkedIn](https://img.shields.io/badge/LinkedIn-Follow%20us%20on%20LinkedIn-blue.svg)](https://www.linkedin.com/company/microchip-technology)
[![Follow us on Facebook](https://img.shields.io/badge/Facebook-Follow%20us%20on%20Facebook-blue.svg)](https://www.facebook.com/microchiptechnology/)
[![Follow us on Twitter](https://img.shields.io/twitter/follow/MicrochipTech.svg?style=social)](https://twitter.com/MicrochipTech)

[![](https://img.shields.io/github/stars/Microchip-MPLAB-Harmony/contentmanager.svg?style=social)]()
[![](https://img.shields.io/github/watchers/Microchip-MPLAB-Harmony/contentmanager.svg?style=social)]()
