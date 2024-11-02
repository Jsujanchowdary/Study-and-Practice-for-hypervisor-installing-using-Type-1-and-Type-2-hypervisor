# Hypervisor Installation Guide

This guide provides a step-by-step approach for installing Type 1 (Bare-Metal) and Type 2 (Hosted) hypervisors, specifically VMware ESXi and VirtualBox.

## Overview

A **hypervisor** (or virtual machine monitor, VMM) is software that creates and manages virtual machines (VMs). There are two main types of hypervisors:

1. **Type 1 Hypervisors**: Also known as **Bare-Metal Hypervisors**, they run directly on the host's hardware.
2. **Type 2 Hypervisors**: Also known as **Hosted Hypervisors**, they run as software on an operating system (OS).

## Type 1: Bare-Metal Hypervisor - VMware ESXi

VMware ESXi is an enterprise-class, Type 1 hypervisor developed by VMware, commonly used for deploying and managing virtual servers.

### Installation Steps for VMware ESXi

1. **Insert Installation Media**  
   Insert the installation DVD or USB stick into the physical server. For virtual servers, map the ISO image to the server and boot from it.

2. **Boot from Installation Media**  
   Choose the standard installer and boot from the ISO image.

3. **Load Installation Files**  
   The installer will load files into memory to prepare for installation.

4. **Welcome Screen**  
   Press `Enter` to start the installation.

5. **Accept License Agreement**  
   Press `F11` to accept the End User License Agreement (EULA) and continue.

6. **Select Installation Disk**  
   The installer will scan for available devices. Choose a disk for ESXi installation and press `Enter`.

7. **Keyboard Layout**  
   Select your preferred keyboard layout and press `Enter`.

8. **Set Root Password**  
   Assign a root password and press `Enter` to continue.

9. **Start Installation**  
   Press `F11` to start the installation.

10. **Complete Installation**  
    After installation completes, remove the installation media and press `Enter` to reboot. The ESXi 7 host is now successfully installed.

## Type 2: Hosted Hypervisor - VirtualBox

Oracle VM VirtualBox is a free and open-source, Type 2 hypervisor for x86 virtualization, developed by Oracle Corporation.

### Installation Steps for VirtualBox

1. **Download VirtualBox**  
   Visit [VirtualBox's website](https://www.virtualbox.org) to download the installer.

2. **Run the Installation Wizard**  
   Open the downloaded file, and the installation wizard will start.

3. **Follow Installation Prompts**  
   Click `Next` or `Yes` as prompted to proceed with the installation.

4. **Install**  
   Click `Install` when prompted.

5. **Finish Installation**  
   Click `Finish` to complete the installation. VirtualBox is now ready for use.

---

## Summary

This guide covered the installation procedures for both VMware ESXi (Type 1) and VirtualBox (Type 2) hypervisors. Each hypervisor serves different purposes based on requirements and system configurations.

## Resources

- [VMware ESXi Documentation](https://www.vmware.com/products/esxi-and-esx.html)
- [Oracle VirtualBox Documentation](https://www.virtualbox.org/manual/UserManual.html)
