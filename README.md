# Ubuntu Gnome Dock Launcher for NVIDIA-SMI

![screenshot](example-use.png)

### What is this ?
* A launcher for the NVIDIA System Management Interface (NVIDIA-SMI) that can be used through the Ubuntu Gnome dock.

* Intended to be used as a convenience, instead of typing the "watch -n0.1 nvidia-smi" in a terminal, every time you want to monitor the status of your Nvidia graphics card (e.g., VRAM and GPU utilization while training deep learning models).

* Tested with Ubuntu 22.04.

### Installation:

* chmod +x install_nvidia_smi_launcher.sh
* sudo --preserve-env=HOME ./install_nvidia_smi_launcher.sh 
* After installation, click on the "Show Applications" button of the Ubuntu Gnome Dock, find the NVIDIA icon of the launcher, right click on it, and select "Add to Favorites".

### Removal:
* chmod +x uninstal_nvidia_smi_launcher.sh
* sudo --preserve-env=HOME ./uninstal_nvidia_smi_launcher.sh 


The NVIDIA icon file used in this project is available under the Creative Commons (Attribution 3.0 Unported) license, from the following link:
https://www.iconfinder.com/icons/4518899/nvidia_icon
