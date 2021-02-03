<h1 align="center">
 <img src="https://user-images.githubusercontent.com/45159366/106686312-ef4cbb00-657e-11eb-92d5-93d7d39b4cf6.png">
  <br />
  Ubuntu Guide
</h1>

### A guide on setting up your Ubuntu Desktop with all the essential Applications, Tools, and Games to make your experience with Ubuntu great!  

# Table of Contents

1. [Getting Started](https://github.com/mikeroyal/Perfect-Ubuntu-Guide/blob/main/README.md#getting-started)

2. [Getting Software](https://github.com/mikeroyal/Perfect-Ubuntu-Guide/blob/main/README.md#getting-software)

3. [GNOME Extensions](https://github.com/mikeroyal/Perfect-Ubuntu-Guide/blob/main/README.md#gnome-extensions)

4. [Advanced Topics](https://github.com/mikeroyal/Perfect-Ubuntu-Guide/blob/main/README.md#advanced-topics)

# Getting Started

[Ubuntu](https://ubuntu.com/) is a modern open source operating system on Linux for the enterprise server, desktop, cloud, and IoT developed by Canonical. Also, checkout the new [Ubuntu Desktop Installer](https://discourse.ubuntu.com/t/refreshing-the-ubuntu-desktop-installer/20659), which will be available to test in the 21.10 release (October 2021) with the Final version being available in the 22.04 LTS release(April 2022).

[Etcher](https://www.balena.io/etcher/) is an open source, cross-platform software that makes it easy to flash operating system images to a microSD card or USB device.

 <img src="https://user-images.githubusercontent.com/45159366/106686328-f5db3280-657e-11eb-9109-88a1df99983a.png">


## Additional Ubuntu Tools/Resources for Enterprise & Small Businesses

[Ubuntu Community Hub](https://discourse.ubuntu.com/)

[Multipass](https://multipass.run/) is a command line interface to launch, manage and generally test with instances of Linux(Ubuntu) in  a VM. It works on Linux, Windows and macOS.

[LXD](https://linuxcontainers.org/lxd/) is a next generation system container manager. It offers a user experience similar to virtual machines but using Linux containers instead. It's image based with pre-made images available for a wide number of Linux distributions and is built around a very powerful, yet pretty simple, REST API.

[MAAS](https://maas.io/) is an open source SDDC solution used by telcos, financial institutions, media companies and supercomputer admins to take care of all the low-level details. PXE, IPMI, ILO and all the custom protocols needed for diverse vendor hardware support come together in one clean REST API with Python bindings for easy integration and automation.

[JuJu](https://juju.is/) is an open source application modeling tool for public and private clouds. It forms part of Ubuntu's cloud portfolio, together with Ubuntu Server, Ubuntu OpenStack, MAAS for bare-metal provisioning, and Landscape for systems management and monitoring.

[JAAS (Juju as a Service)](https://jaas.ai/)  is a service that makes it easy to deploy [OpenStack](https://www.openstack.org/) at scale. Where you quickly and reliably build an enterprise-scale cloud running on Ubuntu.

[Ubuntu OpenStack](https://ubuntu.com/openstack)is the #1 platform for [OpenStack](https://www.openstack.org/) and the #1 platform for public cloud operations on [AWS](https://aws.amazon.com/), [Microsoft Azure](https://azure.microsoft.com/) and [Google Cloud](https://cloud.google.com/).

[Ubuntu is the reference platform for Kubernetes](https://ubuntu.com/kubernetes) on all major public clouds, including official support in Google's GKE, Microsoft's AKS and Amazon's EKS CAAS offerings. 

[Ubuntu on WSL](https://wiki.ubuntu.com/WSL) is a wiki guide on getting started with the latest version of Ubuntu installed and setup on WSL for Windows 10.

[Ubuntu Pro for Azure](https://azuremarketplace.microsoft.com/en-us/marketplace/apps/canonical.0001-com-ubuntu-pro-focal?tab=Overview) is a premium image designed by Canonical optimized for production environments running on Azure. It includes security and compliance services, enabled by default, in a form suitable for small to large-scale Linux enterprise operations with no contract needed. 

[Ubuntu on AWS](https://ubuntu.com/aws)

[Ubuntu on Azure](https://ubuntu.com/azure)


## Setting Up Wayland on Ubuntu

[Wayland](https://wayland.freedesktop.org) is a protocol for a compositor to talk to its clients as well as a C library implementation of that protocol. The compositor can be a standalone display server running on Linux kernel modesetting and evdev input devices, an [X application](https://www.x.org/wiki/XServer/), or a wayland client itself.

**Wayland has been available in Ubuntu since the Ubuntu 17.10 release. Simply go to your login screen and click on Settings in the bottom right corner and select 'Ubuntu on Wayland'. Also, Ubuntu will likely start shipping Wayland by default with their 21.04 release(April 2021).**

 <img src="https://user-images.githubusercontent.com/45159366/106686332-f70c5f80-657e-11eb-944b-8cd85e131539.png">

## Vanilla GNOME in Ubuntu

```sh
sudo apt install gnome-session
```
**Complete this process by Logginh out of the system then will click on the settings button in bottom right corner and choose 'GNOME on Xorg'. After that just log back into your system and you will a Vanilla GNOME layout for your Ubuntu system.**


## GNOME Tweaks

```sh
sudo apt install gnome-tweak-tool //let's you customize your desktop layout.
```

## Enable Firewall

```sh
sudo ufw enable  //enables ubuntu firewall
sudo ufw status //checks status of firewall

# Getting Software

[Back to the Top](https://github.com/mikeroyal/Perfect-Ubuntu-Guide/blob/main/README.md#table-of-contents)

**Note 1: All this software is also available in other popular Linux distributions such as [Debian](https://www.debian.org/), [Linux Mint](https://linuxmint.com/), [elementary OS](https://elementary.io/), [Pop!_OS](https://pop.system76.com/), [Fedora](https://getfedora.org), [Manjaro Linux](https://manjaro.org/), [EndeavourOS](https://endeavouros.com/) and [Arch Linux](https://archlinux.org/).**

**Note 2: For new users not comfortable with using the command-line checkout the Essential Apps section to get started. Also, if you scroll down further you'll see other easy ways to get software applications through Flathub, Snap Store, and AppImages.**

```sh
sudo apt install gnome-software 
sudo apt install snapd
sudo apt install gnome-software-plugin-snap
sudo apt install flatpak
sudo apt install gnome-software-plugin-flatpak
```

## Essential Apps(depending on your workflow)

[Google Chrome browser](https://www.google.com/chrome/)

[Microsoft Edge browser](https://www.microsoftedgeinsider.com/en-us/download/?platform=linux)

[Visual Studio Code](https://code.visualstudio.com/Download)

[Microsoft Teams](https://www.microsoft.com/en-us/microsoft-teams/download-app)

[Microsoft 365 with Office apps](https://www.microsoft.com/en-us/microsoft-365?legRedir=default&CorrelationId=335c4ab6-175d-4c4f-888d-15cfd03e4d32)

[Google Workspace (formerly G Suite)](https://workspace.google.com/)

[Zoom](https://zoom.us/download?os=linux)

[Slack](https://slack.com/downloads/linux)

[Trello](https://trello.com/platforms)

[Skype](https://www.skype.com/en/get-skype/)

[Spotify](https://www.spotify.com/us/download/linux/)

[Discord](https://discord.com/download)

[CrossOver Linux®](https://www.codeweavers.com/crossover) is a Microsoft Windows compatibility layer(based on [WINE(Wine Is Not an Emulator)](https://www.winehq.org)). The CrossOver compatibility layer enables thousands of Windows-based applications to run on Linux, macOS, or Chrome OS.

[DaVinci Resolve video editor](https://www.blackmagicdesign.com/products/davinciresolve/) is complete video editing solution that combines professional 8K editing, color correction, visual effects and audio post production all in one software tool.

[Reaper Audio editor](https://www.reaper.fm/download.php) is a complete digital audio production application for computers, offering a full multitrack audio and MIDI recording, editing, processing, mixing and mastering toolset.

[Flameshot](https://flameshot.org/) is a powerful yet simple to use screenshot software.

[Stacer](https://github.com/oguzhaninan/Stacer) is an open source system optimizer and application monitor that helps users to manage their entire system. Also available as an AppImage.

[Nativefier](https://github.com/nativefier/nativefier) is a command-line tool to easily create a desktop app for any web site with minimal configuration. Apps are wrapped by [Electron](https://www.electronjs.org/) (which uses Chromium under the hood) in an OS executable (.app, .exe, etc) for use on Windows, macOS and Linux.


## App Outlet

[App Outlet](https://app-outlet.github.io/) is a Universal application store(Flatpaks, Snaps, and AppImages) inspired by the Linux App Store online service.

 <img src="https://user-images.githubusercontent.com/45159366/106686354-0095c780-657f-11eb-892b-659d3252d6e7.png">

## Flatpaks

[FlatHub](https://flathub.org/) is a build and distribution service for Flatpak applications.

[FlatHub Forum](https://discourse.flathub.org/)

 <img src="https://user-images.githubusercontent.com/45159366/106686365-055a7b80-657f-11eb-9b58-1de28abe2e5b.png">

## Snaps

[Snap Store](https://snapcraft.io/store) is a build and distribution service for Snap applications.

[Snapcraft Forum](https://forum.snapcraft.io/)

 <img src="https://user-images.githubusercontent.com/45159366/106686375-08ee0280-657f-11eb-9918-5385d8c09148.png">
 <img src="https://user-images.githubusercontent.com/45159366/106686378-0a1f2f80-657f-11eb-83aa-37ac96c7b032.png">

## AppImages

[AppImageHub](https://www.appimagehub.com) is a build and distribution service for AppImage applications.

[AppImage Manager](https://github.com/AppImageCrafters/appimage-manager) is a package manager for AppImages.

[AppImage Forum](https://discourse.appimage.org/)

 <img src="https://user-images.githubusercontent.com/45159366/106686382-0b505c80-657f-11eb-9d74-9a94ec0d0693.png">


## Game Streaming

[Geforce NOW](https://www.nvidia.com/en-us/geforce-now/download/) use the **Chromebook version** to play all your games in Google Chrome or any Chromium-based web browser such as Brave, Vivaldi, and Microsoft Edge. Also, available as a Electron Desktop App in the [Snap store Geforce NOW](https://snapcraft.io/geforcenow).
 <img src="https://user-images.githubusercontent.com/45159366/106686391-0f7c7a00-657f-11eb-9d0b-1ebb4d385883.jpeg">

[Moonlight Game Streaming](https://moonlight-stream.org/) is a program that let you stream from your PC games over the Internet with no configuration required. Stream from almost any device, whether you're in another room or miles away from your gaming rig. 
<img src="https://user-images.githubusercontent.com/45159366/106686398-11463d80-657f-11eb-841a-d534829ccc3d.png">

[Chiaki](https://git.sr.ht/~thestr4ng3r/chiaki) is a Free and Open Source Software Client for PlayStation 4 and PlayStation 5 Remote Play for Linux, FreeBSD, OpenBSD, Android, macOS, Windows, Nintendo Switch and potentially even more platforms.

## Steam

[Get Steam](https://store.steampowered.com/about/)

**Or**

```sh
wget https://steamcdn-a.akamaihd.net/client/installer/steam.deb
```
 <img src="https://user-images.githubusercontent.com/45159366/106686402-13100100-657f-11eb-9012-6bdac264a808.png">

## Lutris

[Lutris](https://lutris.net)is a gaming client for Linux. It gives you access to all your video games with the exception of the current console generation. Also, integrates nicely with other stores like GOG, Steam, Battle.net, Origin, Uplay and many other sources that allow you to import your existing game library and community maintained install scripts give you a completely automated setup.

[Add Epic Games Store](https://lutris.net/games/epic-games-store/)

 <img src="https://user-images.githubusercontent.com/45159366/106686406-14412e00-657f-11eb-97c4-c80c6e25a374.png">
 
 
## Wine

[WINE(Wine Is Not an Emulator)](https://www.winehq.org) is a compatibility layer capable of running Windows applications on several POSIX-compliant operating systems, such as Linux, macOS, & BSD. Instead of simulating internal Windows logic like a virtual machine or emulator, Wine translates Windows API calls into POSIX calls on-the-fly, eliminating the performance and memory penalties of other methods and allowing you to cleanly integrate Windows applications into your desktop.

[Get Wine 6.0](https://www.winehq.org/announce/6.0)


## Winetricks

[Winetricks](https://github.com/Winetricks/winetricks) is an easy way to work around problems in Wine.

this is needed to avoid adobeair error
```sh
sudo sed -i 's|echo "\${arg%%=\*}"=\\""${arg### \*=}"\\"|echo \${arg%%=\*}=\\"\${arg### \*=}\\"|g' /usr/local/bin/winetricks
sudo apt install cabextract libncurses5:armhf
```
## WinApps for Linux

[WinApps for Linux](https://github.com/Fmstrat/winapps) is a program that runs Windows apps such as Microsoft Office & Adobe in Linux (Ubuntu/Fedora) and GNOME/KDE as if they were a part of the native OS, including Nautilus integration for right clicking on files of specific mime types to open them.
