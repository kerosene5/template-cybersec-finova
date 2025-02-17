# Finova Cybersecurity - Task 1: Intro To Linux  #
## Objective ##

Welcome to the Cybersecurity Domain! 

For your first task, you will:

- Install Linux.

## Step 1: Pick
There are 3 ways to install Linux:

- Install Windows Subsystem for Linux (WSL)
- Dual Boot
- Run Linux on a Virtual Machine

Each of these has their own uses but if you are completely new to Linux, WSL is the easiest way to get started.

If you want to completely delve into Linux and use it everyday, Dual Boot is best option for you.

Running Linux on a virtual machine is good for testing out different distros, but other than that, there is not much use.

Pick the option that suits you the most.
  

## 1. Install Windows Subsystem for Linux (WSL) ##

- Open PowerShell as administrator.

- Run: `wsl --install`.

- Restart your computer.

- Launch the installed Linux distribution (Ubuntu) from the Start Menu.

If you would like to install a different distro, run: `wsl --install -d <Distribution Name>`. Replace `<Distribution Name>` with the name of the distro you want to install.

To see a list of available Linux distributions available for download through the online store, enter: `wsl --list --online`.

If you want a detailed guide, go to https://learn.microsoft.com/en-us/windows/wsl/install

Now you have WSL successfully running on your computer!

## 2. Dual Boot 

The process for this depends on the distro that you want. However, as a reference, the guide for installing Ubuntu is given:

- Download the ISO file for Ubuntu: https://ubuntu.com/download
- Create a bootable USB using tools like Rufus.

## Virtual Machine

- Simply install any virtualization software such as VirtualBox or VMWare.
- Setup the VM using the ISO file of the Linux Distro.







