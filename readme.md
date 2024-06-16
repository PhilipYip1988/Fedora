# Fedora

Fedora Setup Guide using a Dell Latitude 9420 2-in-1 Touchscreen Convertible and WD19TB Thunderbolt Dock as an example device.

## System Requirements

The following system requirements should be satisified for a good Fedora experience:

* [System Requirements](./requirements.md)

## Creating Installation Media

The Bootable USB can be created on Windows, Linux and Mac using the Fedora Media Writer:

* [Creating a Bootable USB (Fedora Media Writer - Windows)](./fedora_media_writer_windows.md)

## Updating the BIOS from USB

BIOS Updates are often released in order to accommodate new Operating Systems. It is recommended to make sure your BIOS is up to date before installing Fedora. This can be done from USB for most Dell models manufactured post-2016:

* [Updating the BIOS from USB (Windows)](./bios_update_usb_windows.md)

## BIOS Setup

Some of the BIOS Settings need to be changed in order for Linux to recognise the Storage Device. The Dell Latitude 9420 is used as an example. BIOS Setup screens vary slightly from device to device:

* [BIOS Setup and Data Wipe](./bios_setup.md)

## Live USB Installation

The Live USB uses the USB flash drive as a storage device and runs a number fo services using RAM. It can be used to try Fedora however note that the Live USB may be slow if the read/write speed of the USB Flash Drive si slow. A Fedora Live USB is typically used to being the Fedora Installation:

* [Installation from Live USB](./live_usb.md)

## Out of the Box Setup

The Out of the Box Experience setup is used to create a user account:

* [Out of the Box Setup](./oobe_setup.md)

## GNOME Desktop Environment and Terminal Overview

New users to Linux from Windows should take some time to get accustomed to window management using vanilla GNOME and the Linux Terminal as it is more frequently used than the Windows Terminal. By default binaries (applications) are run as a `user` and can only make changes to the users `home` folder. Binaries can be run as a `super user` in order to make changes elsewhere on the system:

* [GNOME Desktop Environment and Terminal Overview](./vanilla_gnome.md)

## GNOME Tweaks and Extensions

GNOME Tweaks and GNOME Extensions can be used to customise the behaviour of the Desktop Environment. Common customisations make the Desktop Environment behave similar to Ubuntu or Microsoft Windows:

* [GNOME Tweaks and extensions](./tweaks_extensions.md)

## Touchpad 

A mouse with physical buttons and a touchpad with a pressure sensor behave differently by default on GNOME. The touchpad behaviour can be changed to match the mouse using GNOME Settings:

* [Touchpad Behaviour Push and Gestures](./touchpad.md)

## Touchscreen

GNOME is the most advanced Linux Desktop Environment when it comes to 2-in-1 Convertible Touchscreen Devices, offering full touch screen support, making use of the rotation sensor when in tent or tablet mode and includes a touchscreen keyboard. Unfortunately the touchscreen experience is still slightly behind that of Windows and there is no support for the touchscreen keyboard with a Chromium based application, which is otherwise touchscreen friendly:

* [2 in 1 Touchscreen Device](./touchscreen.md)

## Wayland Display Protocol

* WD19TB Dock
    * External Monitors

gsettings set org.gnome.mutter experimental-features "['scale-monitor-framebuffer']"

gsettings set org.gnome.mutter experimental-features "[]"

## Applications 

* GNOME Screen Capture
* Browsers 
    * FireFox
    * Chromium
* Office Applications
    * Libre Office
    * OnlyOffice Desktop Editors
* Paint Applications
    * JSPaint
    * Drawing
    * KolourPaint

## Drivers

* RPM Fusion Installation
    * Linux Kernel VS Third-Party Drivers
    * Disabling Secure Boot
    * Free vs Non-Free
    * Enabling RPM Repositories
    * Webcam Driver


* NVIDIA Driver and Codecs
* RPM Fusion


nvidia driver
 



















In this guide, I look at installation and setup of Fedora 40 on a Dell Latitude (9420) 14 2 in 1 Touchscreen Convertible Device with a WD19TB Thunderbolt Dock. Fedora is the leading edge Linux Distribution and includes Linux Kernel 6.8, the GNOME 46 Desktop Environment and the Wayland Display Protocol. If third-party repositories are enabled, FlatPak packages are installable from Software. Software can seamlessly be used to install new Applications, handles Operating System Updates, Application Updates and Device Firmware Updates via the Linux Vendor Service. This integrated functionality makes Fedora much more logical than most other Linux distributions that typically fragment these components.

Fedora uses a vanilla GNOME however this can be customised using GNOME Tweaks, GNOME Extensions and GNOME Settings as shown in this guide. The GNOME Desktop Environment is the Linux Desktop environment that has the most support for a 2 in 1 Touchscreen Convertible Device exhibiting a Touchscreen Keyboard and Device autorotation out of the box.

* [Tutorial Video](https://www.youtube.com/watch?v=k7ObxUfRqWQ&ab_channel=PhilipYip)

