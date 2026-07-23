<h1 align="center"><b> 🎵 UVR5 UI 🎵 </b></h1>
<div align="center">

[![Open In Colab](https://img.shields.io/badge/Colab-F9AB00?style=for-the-badge&logo=googlecolab&color=525252)](https://colab.research.google.com/github/Eddycrack864/UVR5-UI/blob/main/UVR_UI.ipynb)
[![Open In Kaggle](https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=Kaggle&logoColor=white)](https://www.kaggle.com/code/eddycrack864/uvr5-ui)
<a target="_blank" href="https://lightning.ai/new?repo_url=https%3A%2F%2Fgithub.com%2FEddycrack864%2FUVR5-UI%2Fblob%2Fmain%2FUVR_UI.ipynb">
<img src="https://pl-bolts-doc-images.s3.us-east-2.amazonaws.com/app-2/studio-badge.svg" alt="Open in Studio"/></a>

This project is based on [python-audio-separator](https://github.com/karaokenerds/python-audio-separator) (a CLI version of UVR5).

</div>
<div align="center">
  
[![Hugging Face](https://huggingface.co/datasets/huggingface/badges/resolve/main/open-in-hf-spaces-xl-dark.svg?download=true)](https://huggingface.co/spaces/TheStinger/UVR5_UI)

You can also try it on HuggingFace Spaces running with Zero GPU (A100)!

</div>
 
<div align="center">

</div>

## Features: 
* User Friendly Interface
* All VR Arch Models
* All MDX-NET Models
* Demucs v4 Models
* MDX23C Models
* Mel-Band Roformer Models
* BS Roformer Models
* Music Source Separation Models
* VIP Models
* Separation of an audio/video from all sites supported by [yt_dlp](https://github.com/yt-dlp/yt-dlp). Check the complete list [here](https://github.com/yt-dlp/yt-dlp/blob/master/supportedsites.md).
* Batch Separation
* Available in multiple languages
* Colab/Kaggle/Lightning.ai support
* Windows/Linux support

## Requirements

### Hardware Requirements:
* Nvidia Series 2000 (RTX) or higher.
* At least 10Gb of disk space. 

### Prerequisites:
- Git. You can download Git [here](https://git-scm.com/downloads).
- FFmpeg. You can download FFmpeg [here](https://www.ffmpeg.org/download.html) or you can use my [automated installation script](https://github.com/marpogiii-code/UVR5-UI/blob/main/info/ffmpeg-installer.bat) (for Windows).
- For linux users, run this command on an terminal: (Debian and Ubuntu users): `sudo apt install ffmpeg git` (For Arch linux users): `sudo pacman -S ffmpeg git` (For Fedora users): `sudo dnf install ffmpeg git`
(Some distributions already come with Git and FFmpeg preinstalled so this step may be optional.)

> [!IMPORTANT]  
> FFmpeg has to be added to the PATH. (only needed on Windows)

## Getting Started

Clone the repository (git needed) or download the source code of the latest release [here](https://github.com/marpogiii-code/UVR5-UI/releases)

```
git clone https://github.com/Eddycrack864/UVR5-UI.git
```

Then continue with the steps described below

### 1. Installation

Run the installation script based on your operating system:

- **Windows:** Double-click `UVR5-UI-installer.bat` (DONT RUN AS ADMINISTRATOR 🚧).
- **Linux:** Run `UVR5-UI-installer.sh` with `chmod +x UVR5-UI-installer.sh` and `./UVR5-UI-installer.sh`.

### 2. Running UVR5 UI

Start UVR5 UI using:

- **Windows:** Double-click `run-UVR5-UI.bat`.
- **Linux:** Run `run-UVR5-UI.sh` with `chmod +x run-UVR5-UI.sh` and `./run-UVR5-UI.sh`.

### 3. Update UVR5 UI (If you want/need it)

Update UVR5 UI using (git needed):

- **Windows:** Double-click `UVR5-UI-updater.bat`.
- **Linux:** Run `UVR5-UI-updater.sh` with `chmod +x UVR5-UI-updater.sh` and `./UVR5-UI-updater.sh`.

### 4. Debug (If you want/need it)

Check the status of audio-separator core:

- **Windows:** Double-click `status-checker.bat`.
- **Linux:** Run `status-checker.sh` with `chmod +x status-checker.sh` and `./status-checker.sh`.

## Precompiled Version
1. Get the precompiled version (.zip) for your PC:
   - **[Windows](https://huggingface.co/Eddycrack864/UVR5-UI/tree/main/Windows)**
   - **[Linux](https://huggingface.co/Eddycrack864/UVR5-UI/tree/main/Linux)**

2. Extract the .zip file, I recommend using the "extract here" option.
3. You can now use all the features of the normal installation.

> [!NOTE]  
> Still, to update UVR5 UI you need to install Git.

There is also a pre-compiled version primarily for Chinese users developed by Mar, get it [here](https://www.jian27.com/html/2231.html). Just 2.6 GB! 

## Docker Instance

A more technical level is required for this type of use. You can use this Jupyter notebook to initialize UVR5 on virtual machines with GPU. This will install the entire UVR5 from the main branch of GitHub.

### Requirements/Recommendations
- Use the docker image `>= ubuntu/ubuntu:20.04`
- At least `20 GB of storage minimum.` (Add more space for your models/training)
- Use Jupyter `>= 7.3.1`
- Configure port forwarding `9999 (UVR5-UI GUI)`
- Install necessary drivers to use the GPU

You can get the notebook here: [Jupyter Notebook](https://github.com/marpogiii-code/UVR5-UI/blob/main/UVR_UI_Jupyter.ipynb) by Mar
