# Finova Cybersecurity - Task 1: Intro To Linux  #
## Objective ##

Welcome to the Cybersecurity Domain! 

For your first task, you will:

- Install Linux.

If you already have Linux installed, go to the __Submission__ section

## Step 1: Pick
There are 3 ways to install Linux:

- Install Windows Subsystem for Linux (WSL)
- Dual Boot
- Run Linux on a Virtual Machine

Each of these has their own uses but if you are completely new to Linux, WSL is the easiest way to get started.

If you want to completely delve into Linux and use it everyday, Dual Boot is best option for you.

Running Linux on a virtual machine is good for testing out different distros, but other than that, there is not much use.

Pick the option that suits you the most.
  

## 1. Install Windows Subsystem for Linux (WSL) [Recommended] ##

- Open PowerShell as administrator.

- Run: `wsl --install`.

- Restart your computer.

- Launch the installed Linux distribution (Ubuntu) from the Start Menu.

If you would like to install a different distro, run: `wsl --install -d <Distribution Name>`. Replace `<Distribution Name>` with the name of the distro you want to install.

To see a list of available Linux distributions available for download through the online store, enter: `wsl --list --online`.

If you want an in-depth guide, go to https://learn.microsoft.com/en-us/windows/wsl/install.

Now you have WSL successfully running on your computer!

## 2. Dual Boot 

The process for this depends on the distro that you want. However, as a reference, the guide for installing Ubuntu is given:

- Download the `ISO` file for Ubuntu: https://ubuntu.com/download
- Create a bootable USB drive using tools like `Rufus`.
- Be sure to backup your data incase something goes wrong! (it usually does the first time)
- Plug the USB flashdrive and restart your computer. Enter the BIOS/UEFI settings (press `F12`, `F2` or `Delete` key). 
- Change the boot order to prioritize USB.

After that, you should see a screen like this:
![try-or-install-ubuntu](https://github.com/user-attachments/assets/5e9cbdef-0840-432e-8e17-1c57309f95ff)

Choose the install option, and now you are setup with Ubuntu!


## 3. Virtual Machine

- Simply install any virtualization software such as VirtualBox or VMWare.
- Setup the VM using the ISO file of the Linux Distro.

## Submission

After successfully installing a Linux distro, create a write-up in your repository's `README.md` file using the following format:

```
# Proof of Completion

## Name:
(Your full name)

## Registration Number:
(Your registration number)

## Screenshot of Terminal:
(Attach the screenshot of your Linux terminal)
```

Good luck! Feel free to reach out in the domain-wise WhatsApp group and ask me questions! You can even discuss about the task amongst your peers there.












