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
