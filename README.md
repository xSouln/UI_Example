# Сontent
1. [Repository structure](#repository-structure)
1. [CP210x USB to UART Bridge VCP Drivers](#cp210x-usb-to-uart-bridge-vcp-drivers)
2. [Installation application](#installation-application)
3. [Application description](#application-description)

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
![establish connection](/Images/Screenshot_1.png)

## Figure 2
![establish connection](/Images/Screenshot_2.png)

## Figure 3
![establish connection](/Images/Screenshot_3.png)

## Figure 4
![establish connection](/Images/Screenshot_4.png)

## Figure 5
![establish connection](/Images/Screenshot_5.png)
