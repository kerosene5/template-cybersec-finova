# Finova Cybersecurity - Task 1: Intro To Linux  #

Welcome to the __Cybersecurity__ Domain! 

For your first task, you will:

- Install Linux.

__Linux__ is a freely available open-source operating system initially developed by Linus Torvalds in 1991. 

The term `Linux` can refer to both the _kernel_ itself (the core component of the operating system) and an _operating system_ built around that kernel.

If you already have Linux installed, go to the __Submission__ section.

## Step 1: Choose
There are __3 ways__ to install Linux:

- Install Windows Subsystem for Linux (WSL)
- Run Linux on a Virtual Machine (VM)
- Dual Boot Linux

Each of these has their own uses but if you are completely new to Linux, `WSL` is the easiest way to get started. 

The second option, using a `Virtual Machine`, is something I recommend you do because it allows you to try out multiple linux distros. Also, the __VM__ makes it very easy to undo any mistakes. And trust me, you will make a lot of mistakes!

For people with Apple Silicon Macs (M1, M2, M3), `Virtual Machine` is the recommended approach due to hardware compatibility issues with native installation.

If you want to completely delve into Linux and use it extensively, `Dual Boot` is best option for you. It will give you the full linux performance as well!

__Disclaimer:__ Dual booting can permanently delete all your data if performed incorrectly - always back up everything before proceeding. This process requires technical knowledge of partitioning and boot management; mistakes can render your computer unusable. __If you are not sure, then try out the other methods instead!__

__Pick the option that interests you the most!__
  

## 1. Install Windows Subsystem for Linux (WSL) [Windows Users Only]

- Open __PowerShell__ as administrator.

- Run: `wsl --install`.

- __Restart__ your computer.

- Launch the installed Linux distribution (Ubuntu) from the __Start Menu__.

- On first launch, create a `username` and `password` for your Linux distribution.

- After you have launched Ubuntu, __run:__ `sudo apt update`.

- Install the neofetch command: `sudo apt install neofetch`. When prompted, __press `Y`.__

- __Type `neofetch` in your WSL terminal.__ You should get an output like so:
<img width="769" alt="{644586C6-08C8-4405-8D62-9B973DF9F45C}" src="https://github.com/user-attachments/assets/b5831f23-1306-4ee6-a57c-d77af3d62795" />


If you would like to install a different distro, run: `wsl --install -d <Distribution Name>`. Replace `<Distribution Name>` with the name of the distro you want to install.

To see a list of available Linux distributions available for download through the online store, enter: `wsl --list --online`.

If you want to learn more about WSL, go to https://learn.microsoft.com/en-us/windows/wsl/install.

__Now you have WSL successfully running on your computer!__

## 2. Virtual Machine

- Download and install [VirtualBox](https://www.virtualbox.org/wiki/Downloads) from the official website.
- Download the __ISO file__ for Ubuntu: https://ubuntu.com/download
- Open __VirtualBox__ and click `New` to create a virtual machine.
- Name your VM, select `Linux` as type, and choose the appropriate version (e.g., Ubuntu)
- __Allocate memory (RAM)__ - at least `2048 MB (1GB)` recommended.
- Select the type of Hard disk. Using __VDI type__ is recommended. 
- Create a virtual hard disk __(select "Dynamically allocated")__
- Set the storage size (`minimum 10GB recommended`)
- Select your new VM and __click `Start`__
- When prompted, __select your downloaded Linux ISO file.__
- __Follow the Linux installation process, selecting "Erase disk and install" (this only affects the virtual disk)__

![Ubuntu-VirtualBox-Installation-13](https://github.com/user-attachments/assets/5faa3c9b-5a83-4fed-96e9-b86c5874248d)

- Create your `user account` and complete installation.
- __Restart the VM to start using Linux!__

After your setup, you should get an output like so:

<img width="600" alt="{68D5CE10-9761-4B83-B54B-34563F61EC2E}" src="https://github.com/user-attachments/assets/7af76bd8-8cc9-4c5f-be6b-ec5771aa47d4" />

for a more in-depth guide, check this out: https://www.geeksforgeeks.org/how-to-install-ubuntu-on-virtualbox/

__Congrats, you successfully installed Ubuntu on a Virtual Machine!__

## 3. Dual Boot 

__Again, please proceed with caution. Dual booting can permanently delete all your data if performed incorrectly.__

__If you are a beginner, I recommend you try the other methods.__

The process for this depends on the distro that you want. However, as a reference, the guide for dual-booting Ubuntu with Windows is given:

__Prerequisites:__
- It is recommended that you have 100 – 150 GB of free Hard Disk space, although anything above 40 GB would do the job. __(This step is important as it is the amount of space you will be dedicated to your Linux OS, and once Linux is installed you will not be able to access this space through Windows)__
- A USB flash drive that has a minimum space of 8 GB.

__Preparation:__
- __Back up all important data.__
- __Disable Fast Boot__ in Windows for proper system closure.
- Download the `ISO` file for __Ubuntu__: https://ubuntu.com/download
- Download and install [Rufus](https://rufus.ie/en/) to create a __bootable USB__.
- __Create__ a bootable USB with your Linux ISO.
- Enter Windows Disk Management Service. You can go to `Run` enter `diskmgmt.msc` and run.
- On the Disk Management Window right click on the Partition from which you want to extract the required (recommended 100 – 150 Gb) amount of free space, and __click on ‘Shrink Volume’.__
- Enter the ‘amount of space to shrink’ as 102400 Mb (100 Gb) and continue. This would reduce the space of the present volume by 100 Gb and the remaining 100 Gb would be shown as Unallocated Space (for you to install Linux on).


__Installation:__
- __Insert__ your bootable USB flashdrive and restart your computer.
- Enter your __BIOS/UEFI settings__ by repeatedly pressing the appropriate key during startup (often Delete, F2, F10 or F12).
- Set the __USB drive__ as the first boot device.
- __Save changes__ and exit BIOS.

__Linux Setup:__
- __Boot from the USB.__
  
You should see a screen like this:

![try-or-install-ubuntu](https://github.com/user-attachments/assets/5e9cbdef-0840-432e-8e17-1c57309f95ff)

- __Select "Try or Install Ubuntu"__.
- After this, you will be taken to __Ubuntu Setup__ and required to partition your disk. Go to https://www.geeksforgeeks.org/setup-dual-boot-with-linux-and-windows/ for detailed steps on how to create a partition for Linux and complete the setup.


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

Good Luck! If you have any questions, or you got stuck along the way, feel free to ask me questions in the WhatsApp groupchat! You can even discuss about your tasks there.
