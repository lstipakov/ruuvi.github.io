---
title: Getting started
template: guide.hbs
columns: two
order: 2
---

# Getting Started
## Unboxing
![](/assets/images/getting-started/box.jpg)
Congratulations on being the owner of a brand new Ruuvi device! Go ahead and open the box.

### What's on it?
![](/assets/images/getting-started/contents.jpg)
This is RuuviTag. RuuviTag is an **Open-Source Sensor Beacon Platform**. It's super easy and straightforward to fire it up, so let's get started, shall we?

## What you need?
In this example, we will start the device for the first time and upload a demo application into its memory. Prerequisities:
* **Software**
  * Mobile Application - [iOS](https://itunes.apple.com/us/app/nrf-toolbox/id820906058) | [Android](https://play.google.com/store/apps/details?id=no.nordicsemi.android.nrftoolbox)
* **Hardware**
  * Your brand new RuuviTag device
  * iPhone or Android smartphone
* **Experience**
  * None!

### Step 1: Power on
![](/assets/images/getting-started/tag.jpg)
Insert a battery (CR2430, CR2450 or CR2477) so that metallic battery connnector touches negative GND pad of the battery. One of the LEDs should be lit (on, not blinking). Now the device is in operational mode and pre-installed bootloader software is running.

### Step 2: Upload an application
![](/assets/images/getting-started/rssi.jpg)
By using nRF Master Control Panel app ([iOS](https://itunes.apple.com/us/app/nrf-master-control-panel-ble/id1054362403) | [Android](https://play.google.com/store/apps/details?id=no.nordicsemi.android.mcp)), you can see the device. No need to do this however, but sometimes it's handy.
![](/assets/images/getting-started/dfu.jpg)
1. Check what ready-made example applications [we have to offer](/guide/getting-started/examples). We are coding all the time and the selection will grow in the near future.
2. Open the nRF Toolbox mobile application and tap **DFU** (device firmware update) icon.
3. Select **application file**. Correct file type is **Distribution package (ZIP)**. By default, the application tries to find the file from your Dropbox folder. If it's convenient for you, put it there and select it.
4. Hit **Select device** button. The phone scans nearby Bluetooth Smart devices and **DfuTarg** will show up on your screen. Select it.
5. Press **UPLOAD** and the magic happens.

The bootloader is a _"dual bank"_ bootloader. This means it's not possible to brick the device while updating the application code.

### Step 3: It's alive!

After Over-the-Air _(OTA)_ Device Firmware Update _(DFU)_ is completed, RuuviTag starts to run the application code automatically. Success!

### Casing
Note, that the product box can be used as an enclosure on indoor applications.