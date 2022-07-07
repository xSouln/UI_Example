# Сontent
1. [Repository structure](#repository-structure)
1. [CP210x USB to UART Bridge VCP Drivers](#cp210x-usb-to-uart-bridge-vcp-drivers)
2. [Installation application](#installation-application)
3. [Device connection](#device-connection)
4. [Application description](#application-description)

## Repository structure
- folder [Desktop](/Desktop) - contains custom application files.
- folder [Drivers](/Drivers) contains:
    - driver [CP210x USB to UART Bridge VCP Drivers](#cp210x-usb-to-uart-bridge-vcp-drivers).
    - archiver [7-Zip](https://downgit.github.io/#/home?url=https://github.com/xSouln/UI_Example/tree/main/Drivers/7z2200-x64.exe) or [link](https://www.7-zip.org/) from the official site.

## CP210x USB to UART Bridge VCP Drivers
- download the driver from this [link](https://downgit.github.io/#/home?url=https://github.com/xSouln/UI_Example/tree/main/Drivers/CP210x_Windows_Drivers.zip) or from the official [website](https://www.silabs.com/developers/usb-to-uart-bridge-vcp-drivers).

## Installation application
- install [CP210x USB to UART Bridge VCP Drivers](#cp210x-usb-to-uart-bridge-vcp-drivers)
- download the [application](/Desktop) from the [link](https://downgit.github.io/#/home?url=https://github.com/xSouln/UI_Example/tree/main/Desktop).
- unzip the archive. If necessary, install the [archiver](https://www.7-zip.org/).
- to run the application use the file ["name of the unpacked archive"/Examples_CSharpFramework.exe]().

## Device connection
- connect the battery with a red lead to the red arrow as shown in the [Figure 9](#figure-9).
- connecting the [USB to UART Bridge] device to the USB connector of the computer - [Figure 6](#figure-6).
- turn on the device, pinch the contact [TP53](#figure-8) with your finger - [Figure 7](#figure-7).

## Application description
- connect device via usb
- launch the application [Examples_CSharpFramework.exe]()
- establish connection:
    - select the connection interface "Connections" => "Serial port" - [Figure 1](#figure-1).
    - in the window that opens - [Figure 1](#figure-2), select the COM port, enter "Boud rate" = 512000 and set the "Port name" corresponding to the port number "Silicon Labs CP210x USB to UART Bridge" - [Figure 3](#figure-3).
    - to connect, click the "Connect" button, if the connection is successful, the "Connect" button will turn green - [Figure 4](#figure-4).
- additional features:
    - to clear the charts, right-click on the chart area and click "Clear" in the context menu that opens - [Figure 5](#figure-5). 

## Figure 1
### select the [serial port]() connection interface
![establish connection](/Images/Screenshot_1.png)

## Figure 2
### serial port window
![establish connection](/Images/Screenshot_2.png)

## Figure 3
### display [Silicon Labs CP210x USB to UART Bridge]() device in Windows Device Manager
![establish connection](/Images/Screenshot_3.png)

## Figure 4
### successful connection status
![establish connection](/Images/Screenshot_4.png)

## Figure 5
### clearing graph data
![establish connection](/Images/Screenshot_5.png)

## Figure 6
### connecting the [Silicon Labs CP210x USB to UART Bridge]() device to the USB connector
![establish connection](/Images/photo_1.jpeg)

## Figure 7
### turn on the device with a touch of a finger
![establish connection](/Images/photo_2.jpeg)

## Figure 8
### contact [TP53]() - circled in red
![establish connection](/Images/Screenshot_6.png)

## Figure 9
### battery connector, the red arrow indicates the connection point of the contact with the red wire
![establish connection](/Images/photo_3.jpeg)
