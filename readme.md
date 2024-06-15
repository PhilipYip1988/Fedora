# Fedora

## Creating Installation Media

The Bootable USB can be created on Windows, Linux and Mac using the Fedora Media Writer:

* [Creating a Bootable USB Using the Fedora Media Writer Windows](./fedora_media_writer_windows.md)

## Updating the BIOS from USB

BIOS Updates are often released in order to accomodate new Operating Systems. It is recommended to make sure your BIOS is up to date before installing Fedora.

* [Updating the BIOS from USB Windows](./bios_update_usb.md)

## BIOS Setup

Some of the BIOS Settings need to be changed in order for Linux to recognise the Storage Device:

* [BIOS Setup and Data Wipe](./bios_setup.md)

## Live USB Installation

* [Installation from Live USB](./live_usb.md)

## Out of the Box Setup

* [Out of the Box Setup](./oobe_setup.md)

## GNOME Desktop Environmentn and Terminal Overview



## Drivers

* NVIDIA Driver and Codecs
* RPM Fusion


nvidia driver
 



















In this guide, I look at installation and setup of Fedora 40 on a Dell Latitude (9420) 14 2 in 1 Touchscreen Convertible Device with a WD19TB Thunderbolt Dock. Fedora is the leading edge Linux Distribution and includes Linux Kernel 6.8, the GNOME 46 Desktop Environment and the Wayland Display Protocol. If third-party repositories are enabled, FlatPak packages are installable from Software. Software can seamlessly be used to install new Applications, handles Operating System Updates, Application Updates and Device Firmware Updates via the Linux Vendor Service. This integrated functionality makes Fedora much more logical than most other Linux distributions that typically fragment these components.

Fedora uses a vanilla GNOME however this can be customised using GNOME Tweaks, GNOME Extensions and GNOME Settings as shown in this guide. The GNOME Desktop Environment is the Linux Desktop environment that has the most support for a 2 in 1 Touchscreen Convertible Device exhibiting a Touchscreen Keyboard and Device autorotation out of the box.

* [Tutorial Video](https://www.youtube.com/watch?v=k7ObxUfRqWQ&ab_channel=PhilipYip)
* [System Requirements](./requirements.md)
* Creating a Bootable USB 
    * On Windows with Rufus
    * On Fedora with Fedora Media Writer
* UEFI BIOS Update Via USB
* UEFI BIOS Settings
* Storage Controller
    * Boot Sequence
    * Using Dell Data Wipe to Securely Wipe Internal Drives
    * Preboot Behaviour (Minimal Fast Boot vs Through Fast Boot)
* Booting from USB
    * Fedora Live USB and Installation
    * Fedora Setup
* RPM and FlatHub Third Party Repositories
* Welcome Tour and GNOME Desktop Environment
* Software Update
    * OS and App Updates
    * Firmware Update
* Touchpad
    * Gestures
    * Two Finger Push
    * Corner Push
* Touchscreen
    * Accessibility Menu and Screen Keyboard
    * Device Rotation
* WD19TB Dock
    * External Monitors
* Applications
    * Browsers 
        * FireFox
        * Chromium
    * Office Applications
        * Libre Office
        * OnlyOffice Desktop Editors
    * Paint Applications
        * Drawing
        * KolourPaint
    * GNOME Screen Capture
* GNOME Tweaks
* GNOME Extensions (Official)
* GNOME Extension Manager (Third-Party)
    * Dash to Dock Extension
    * Desktop Icons NG Extension
    * Clipboard History Extension
    * Show Desktop Extension
    * Tiling Assistant Extension
    * GTile Extension
* RPM Fusion Installation
    * Linux Kernel VS Third-Party Drivers
    * Disabling Secure Boot
    * Free vs Non-Free
    * Enabling RPM Repositories
    * Webcam Driver