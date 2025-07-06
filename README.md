# STM32 Scratch Repository

## Overview

This codebase is a short example of how to keep an STM32CubeIDE project in GitHub and have it work across machines. The code itself is a simple example of using USB-HID input using a microUSB port and controlling a little OLED screen with SPI.

IMPORTANT: I am not sure but I think the versions of STM32CubeIDE need to be identical for this to work smoothly. The version used for the development of this codebase is 1.18.1

## Setting up a new STM32CubeIDE Repo
Key: The .ioc file must be named the same as the root folder of your project (the repository name)

## Cloning and using an existing STM32CubeIDE Repo


1. Clone the Repo:
2. Launch the IDE
3. Import the Project:
    > File > Import > General > Existing Projects into Workspace
4. Specify project path with "Select root directory"
5. Make sure "Copy projects into workspace" is unchecked
6. Finish
7. Go ahead and build the project to make sure it works
8. Also make sure to check that the .ioc file loads correctly


## Authors

- b5050d