# Finova Cybersecurity - Task 1: Intro To Linux  #

Welcome to the __Cybersecurity__ Domain! 

For your first task, you will:

- Install Linux.

__Linux__ is a freely available open-source operating system initially developed by Linus Torvalds in 1991. 

The term `Linux` can refer to both the _kernel_ itself (the core component of the operating system) and an _operating system_ built around that kernel.

If you already have Linux installed, go to the __Submission__ section.

## Step 1: Pick
There are 3 ways to install Linux:

- Install Windows Subsystem for Linux (WSL)
- Dual Boot Linux
- Run Linux on a Virtual Machine (VM)

Each of these has their own uses but if you are completely new to Linux, `WSL` is the easiest way to get started. 

If you want to completely delve into Linux and use it extensively, `Dual Boot` is best option for you. It will give you the full linux performance as well!

The third option, using a `Virtual Machine`, is something I recommend you do because it allows you to try out multiple linux distros. Also, the __VM__ makes it very easy to undo any mistakes. And trust me, you will make a lot of mistakes!

__Pick the option that interests you the most!__
  

## 1. Install Windows Subsystem for Linux (WSL) [Windows Users Only]

- Open __PowerShell__ as administrator.

- Run: `wsl --install`.

- Restart your computer.

- Launch the installed Linux distribution (Ubuntu) from the __Start Menu__.

- On first launch, create a `username` and `password` for your Linux distribution.

- After you have launched Ubuntu, run: `sudo apt update`.

- Install the neofetch command: `sudo apt install neofetch`. When prompted, press `Y`.

- Type `neofetch` in your WSL terminal. You should get an output like so:
<img width="769" alt="{644586C6-08C8-4405-8D62-9B973DF9F45C}" src="https://github.com/user-attachments/assets/b5831f23-1306-4ee6-a57c-d77af3d62795" />


If you would like to install a different distro, run: `wsl --install -d <Distribution Name>`. Replace `<Distribution Name>` with the name of the distro you want to install.

To see a list of available Linux distributions available for download through the online store, enter: `wsl --list --online`.

If you want to learn more about WSL, go to https://learn.microsoft.com/en-us/windows/wsl/install.

Now you have WSL successfully running on your computer!

## 2. Dual Boot 

The process for this depends on the distro that you want. However, as a reference, the guide for dual-booting Ubuntu with Windows is given:

- Download the `ISO` file for __Ubuntu__: https://ubuntu.com/download
- Download and install [Rufus](https://rufus.ie/en/) to create a __bootable USB__.
- Create a bootable USB with your Linux ISO.
- Be sure to backup your data incase something goes wrong! (it usually does the first time)
- Plug the __USB flashdrive__ and restart your computer. Enter the BIOS/UEFI settings (repeatedly press `F12`, `F2` or `F10` key). 
- Change the boot order to prioritize USB. Then, boot from the USB.

After that, you should see a screen like this:
![try-or-install-ubuntu](https://github.com/user-attachments/assets/5e9cbdef-0840-432e-8e17-1c57309f95ff)

Choose the `Install Ubuntu` option, and now you have successfully dual booted Ubuntu!

After this, you will have to complete your installation setup. While doing so, you will be asked: `How do you want to partition the disk?`.

It's recommended you free up at least 10 GB of free space for your Ubuntu install.

For a more in-depth guide, go to: https://help.ubuntu.com/community/WindowsDualBoot



## 3. Virtual Machine

- Download and install [VirtualBox](https://www.virtualbox.org/wiki/Downloads) from the official website.

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












