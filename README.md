## Netduino MacDeploy Tool

Updates firmware on Netduinos on Mac, yay!

![](MacDeploy/MacDeployTool.png)

## Netduino Firmware Releases
A repository of Netduino Firmware binaries. These are built from the [Netduino SDK](https://github.com/WildernessLabs/Netduino_SDK) sources. They can be uploaded to Netduinos either via MFDeploy (on windows), or Mac Deploy Tool (coming _very_ soon, for Mac).

### Current Pre-Release

**[4.3.2.4pre2](Firmware/Pre-Release/4.3.2.4pre2)** - This is a pack of v4.3.2.3, but built on a newer compiler. It should be equivalent to the official 4.3.2.3 release, except that it _may_ contain a fix for [Issue #1](Firmware/https://github.com/WildernessLabs/Netduino_SDK/issues/1)

This releases fixes the `NetworkInterface` issue found in 4.3.2.4pre.

#### Older Pre-releases

**[4.3.2.4pre](Firmware/Pre-Release/4.3.2.4pre)** - This is a pack of v4.3.2.3, but built on a newer compiler. It should be equivalent to the official 4.3.2.3 release, except that it _may_ contain a fix for [Issue #1](https://github.com/WildernessLabs/Netduino_SDK/issues/1)

## Uploading Firmware to Device


### On Mac using the MacDeploy Tool

#### Automatic Installation of Latest Official Firmware

 1. Open the latest MacDeploy tool.
 2. Click the `Install Firmware` button, firmware should install:
 ![](MacDeploy/MacDeploy_AutomaticFirmwareUpdate.png)
 

#### Manual Installation of Firmware from .hex or .s19 files

 1. Open the latest MacDeploy tool.
 2. Click the `Choose` button, and select either the `.hex` or `.s19` `ER_CONFIG` and `ER_FLASH` files:

 