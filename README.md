# Virtual Machine Setup Guide

This repository provides step-by-step instructions to set up and run a virtual machine using a preconfigured VDI file.

## Prerequisites

1. Ensure at least **100GB** of free space on your C or D drive.
2. Download the VDI file:
   - [vsdsquadron.vdi](https://forgefunder.com/~kunal/vsdsquadron.vdi)
3. Install **Oracle VirtualBox**:
   - [Download for Windows](https://www.virtualbox.org/wiki/Downloads)
   - Install on Ubuntu using the command:
     ```bash
     sudo apt install virtualbox
     ```

## Setup Instructions

### Windows

1. Install and launch Oracle VirtualBox.
2. Click **New** to create a virtual machine:
   - Set OS type to **Linux**, version **Ubuntu 18.04**.
3. Allocate memory as required.
4. Choose **Use an existing virtual hard disk file**, and select the downloaded VDI file.
5. Complete the setup and start the VM.

### Ubuntu

1. Install VirtualBox via the terminal:
   ```bash
   sudo apt install virtualbox
2.Launch VirtualBox by running:
  bash
  copy code
  virtualbox

3.Create a new virtual machine:
Set OS type to Linux, version Ubuntu 18.04.

4.Allocate memory and select the downloaded VDI file.

5.Complete the setup and start the VM.

**Usage**
Once the virtual machine boots up, you can use it like a physical computer inside a virtual environment.
References

Oracle VirtualBox Official Site

VDI File Download

javascript
Copy code

You can save this file as `README.md` in the root directory of your GitHub repository. Let me know if you need additional details!



















