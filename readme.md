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

 - [Release Notes](./release_notes.md)
 - [MPLAB® Harmony 3 MHCM Wiki](https://github.com/Microchip-MPLAB-Harmony/contentmanager/wiki)

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

| Library Name                         	        | License                                                                                   |
|-----------------------------------------------|-------------------------------------------------------------------------------------------|
| jsch-0.1.54.jar								| Revised BSD http://www.jcraft.com/jsch/LICENSE.txt                                        |
| jsoup-1.10.2.jar                             	| The MIT License https://jsoup.org/license                                                 |
| org.eclipse.jgit-4.11.0.201803080745-r.jar   	| Eclipse Distribution License (New BSD License)                                            |
| simple-xml-2.7.1.jar                         	| The Apache Software License, Version 2.0 http://www.apache.org/licenses/LICENSE-2.0.txt   |
| slf4j-api-1.7.25.jar                         	| MIT License http://www.opensource.org/licenses/mit-license.php                            |
| slf4j-simple-1.7.25.jar                      	| MIT License http://www.opensource.org/licenses/mit-license.php                            |
