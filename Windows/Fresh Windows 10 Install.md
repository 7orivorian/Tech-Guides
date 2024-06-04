# Windows 10 Fresh Installation Guide

### Hardware Requirements

- An empty USB drive with at least 8GB of storage.
- A working computer with an internet connection & a USB port.
- The computer you wish to do a fresh Windows 10 install on.
    - Specific requirements can be
      found [here](https://www.microsoft.com/en-us/windows/windows-10-specifications#areaheading-uid09f4).

## Preparation

### Backup Your Data

> [!CAUTION]
> Doing a fresh Windows installation will remove everything on your computer!

Before starting, back up all important data to an external drive, cloud storage,
or another computer.

### Create Installation Media

With a working computer (not the computer you want to install Windows on):

- Plug your USB drive into the working computer.
- Visit
  the [official Microsoft website](https://www.microsoft.com/en-us/software-download/windows10)
    - Under **Create Windows 10 installation media**, click `Download Now`.
- Run the downloaded tool. It may take a minute to set up.
    - When prompted `What do you want to do?`, click `Create installation
      media`
    - Select language, arch, and edition. Make sure Edition is Windows 10.
    - When prompted `Choose which media to use`, click `USB flash drive`.
    - Select your removable USB drive from the list of available drives.
      (Note that the selected USB drive will be completely wiped).
    - Wait while Windows 10 is downloaded. This may take a while.

## Installation

### Boot from USB Drive

- Plug the USB drive into the PC you wish to install Windows onto.
- Boot the PC (if the PC is already on, either restart it or power off &
  power back on).
- Enter the BIOS/UEFI setup by mashing the F2/F12/Delete/Esc key while the PC is
  starting. If you
  don't know which key to use, either keep restarting & try them all, or google
  your motherboard.
- Set the USB drive as the primary boot device. (This varies by motherboard,
  so if it isn't obvious, Google it!)
- Save & exit the BIOS. The computer should now boot from the USB drive. You
  may have to save & reboot.

### Windows Setup

- Choose your language, time, and keyboard preferences, then click `Next`.
- Click `Install now`.
- Enter your Windows 10 product key or click `I don't have a product key` to
  enter it later.
- Accept the license terms and click `Next`.

### Choose Installation Type

- Select `Custom: Install Windows only (advanced)`.
- You will see a list of existing partitions on your hard drive. These
  partitions might be labeled as "Drive 0 Partition 1," "Drive 0 Partition 2,"
  etc.
    - Click on each partition and select `Delete`. Confirm any warnings.
    - You should now see a single entry labeled "Drive 0 Unallocated Space"
      or similar.
- With all partitions deleted, select the unallocated space and click `New`.
- Set the size (use the maximum available if you're unsure), and click
  `Apply`.
- Choose the newly created primary partition and click `Next`.

# Post Installation

- Update Windows:
    - Go to Settings > Update & Security > Windows Update and click `Check for
      updates`. Install all available updates.