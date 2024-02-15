# Activity 1

### Steps 

1. Install VirtualBox
2. Install Lubuntu
3. Take snapshot
4. Disable GUI

### VirtualBox

- Download and install Oracle VM VirtualBox from the official website: [VirtualBox Downloads](https://www.virtualbox.org/).
- Follow the installation instructions for your operating system.
  - How to install VirtualBox [on Mac](https://cs.hofstra.edu/docs/pages/guides/vbox_mac.html)
  - How to install VirtualBox [on Windows](https://cs.hofstra.edu/docs/pages/guides/vbox_windows.html)
- `Optional step`: Download and install the [extension pack](https://www.virtualbox.org/)

### Install Lubuntu

1. Download Lubuntu from the official [Lubuntu website.](https://lubuntu.me/)

2. **Create a New Virtual Machine:**
   - Open VirtualBox.
   - Click on the "New" button in the top-left corner to create a new virtual machine.
   - Enter a name for your virtual machine (e.g., "Lubuntu 20.04").
   - Select "Linux" as the type and "Ubuntu (64-bit)" as the version.
   - Click "Next."

3. **Allocate Memory (RAM):**
   - Allocate 2048MB (2GB) of memory (RAM) to the virtual machine.
   - Click "Next."

4. **Create Virtual Hard Disk:**
   - Select "Create a virtual hard disk now" and click "Create."
   - Choose the hard disk file type. The default "VDI (VirtualBox Disk Image)" is fine.
   - Choose dynamically allocated disk space.
   - Allocate 25GB of disk space for the virtual hard disk.
   - Click "Create."

5. **Configure Virtual Machine Settings:**
   - Select the newly created virtual machine from the VirtualBox Manager.
   - Click on "Settings."
   - Under "System," go to the "Processor" tab and allocate the desired number of CPU cores.
   - Under "Storage," select the empty CD drive, then click on the CD icon on the right side and choose "Choose a disk file." Select the Lubuntu 20.04 ISO file you downloaded.
   - Click "OK" to close the settings.

6. **Start the Virtual Machine:**
   - With the virtual machine selected, click the "Start" button in the VirtualBox Manager.
   - The Lubuntu installer should boot from the ISO file.

7. **Install Lubuntu:**
   - Follow [these steps](https://www.tecmint.com/install-lubuntu/). 

8. **Eject ISO and Restart:**
   - After the installation is complete, shut down the virtual machine.
   - Go to the settings of the virtual machine, navigate to "Storage," and remove the Lubuntu ISO file from the virtual CD/DVD drive.
   - Start the virtual machine again.

9. **Login and Configure:**
    - After restarting, you'll be prompted to log in to your newly installed Lubuntu virtual machine.
    - Log in with the username and password you created during the installation process.


### Disable GUI

> Before disabling the GUI, it's important to take a snapshot of the virtual machine.

1. Run the following commands
```bash
$ sudo apt update && sudo apt upgrade
$ sudo apt install gnome-session-bin

```

2. The following command will disable GUI on boot hence upon the reboot the system will boot into multi user target:
```bash
 $ sudo systemctl set-default multi-user
```
3. Reboot or log out from a current session to exit GUI:
```bash
$ gnome-session-quit
```

### Start GUI manually from a command line

- To start GUI manually from a command line
```bash
$ sudo systemctl isolate graphical
# or
$ startx
``` 

- To enable GUI to start on boot
```bash
$ sudo systemctl set-default graphical
```


- Install VirtualBox Guest Additions on Ubuntu
```bash
sudo apt update
sudo apt upgrade
sudo apt install build-essential dkms linux-headers-$(uname -r)
``` 
Next, from the Virtual Machine menu bar, go to “Devices” and click on "Insert Guest Additions CD image." This helps to mount the Guest Additions ISO file inside your virtual machine.

<!-- 
- (For Gnome) To start GUI manually from a command line
```bash
sudo systemctl start gdm3
```
-->

<!-- 
- Install VirtualBox Guest Additions on Ubuntu
```bash
sudo apt update
sudo apt upgrade
sudo apt install build-essential dkms linux-headers-$(uname -r)
``` 
Next, from the Virtual Machine menu bar, go to “Devices” and click on "Insert Guest Additions CD image." This helps to mount the Guest Additions ISO file inside your virtual machine.
https://linuxiac.com/ubuntu-with-virtualbox/
-->

- [Ref](https://linuxconfig.org/how-to-disable-enable-gui-on-boot-in-ubuntu-20-04-focal-fossa-linux-desktop)
