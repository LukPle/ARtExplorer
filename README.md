# ARtExplorer
**Immerse yourself in a new way of exploring art interactively**<br>
An augmented reality application for the Microsoft HoloLens®, developed using the Unity Game Engine<br>
<br>

## Table of Contents
- [About](#about)
- [Contributors](#contributors)
- [Installation](#installation)
- [Run on Headset](#run-on-headset)
<br>

## About
ARtExplorer lets you see art like never before:
- View selected paintings and discover virtual objects emerging from the artwork
- Interact with these objects by moving, rotating, and resizing them
- Gain fresh perspectives and explore additional details
- Combine elements from different paintings to create unique compositions
- Integrate virtual objects into your physical surroundings
- Compare the objects with the original paintings to enhance your understanding
- Access additional information and insights about each artwork
<br>

<img src="https://github.com/user-attachments/assets/cb29fc58-1e10-4f93-8a12-284677844253" alt="Ship_Interaction_HoloLens" width="400"/>
<img src="https://github.com/user-attachments/assets/83a1e1bc-a045-467b-9560-0c00c15808d8" alt="Both_Paintings_HoloLens" width="400"/>
<img src="https://github.com/user-attachments/assets/64449638-0a8f-4df2-ae69-30db92e6e531" alt="Combine_Paintings_HoloLens" width="400"/>
<img src="https://github.com/user-attachments/assets/0a89ec41-42bf-45da-9c7e-722d6f03b726" alt="User" width="400"/>
<br><br>

Used Packeges:
- Vuforia for Image Detection
- MRTX2 for HoloLens® Functionalities
<br>

## Contributors
- [Barbara Seidinger](https://github.com/BarbaraSe), User Interface Design and Gesture Tracking
- [Michelle Zender](https://github.com/mimizen), Menu Interaction Development and Scripting
- [Amiin Najjar](https://github.com/najjar77), App Setup and 3D Model Design
- [Lukas Plenk](https://github.com/LukPle), Image Recognition, Model Placement and Interactions
<br>

## Installation
Before you can start with development, ensure you have the following installed:

1. **Unity Hub**: Download and install Unity Hub from the official [Unity Website](https://unity.com/de/download)
2. **Unity Game Engine**: Go Installs > Install Editor > Archive and then download the 2022.3.21f Version
3. **Visual Studio 2022**: Comes with the Engine - You can also install it manually from the offical [Visual Studio Website](https://visualstudio.microsoft.com/de/downloads/)
4. **Required Modules**: Add these Modules to your Visual Studio Installation
   1. Python Development
   2. Desktop Development with C++
   3. Universal Windows Platform Development including all optional C++ tools
   4. Game Development with Unity
   5. Game Development with C++
<br>

Clone the Repository:

```sh
git clone https://github.com/LukPle/ARtExplorer.git
cd ARtExplorer
```
<br>

## Run on Headset
**Unity**
1. Setup Build Setting (File > Build Setting): ARM 64-bit, D3D Project, Latested Installed, 10.0.10240.0, Visual Studio 2022, Local Machine, Release
2. Build: Save inside Folder 'Install' - Create this Folder on first build

**Visual Studio**
1. Open Folder Install and the '.sln' File
2. Settings UI: WIFI: Debug, ARM64, Remote Machine / USB: Release, ARM64, Device
4. On the Right Side Panel select Universal Windows
5. For Remote Build: Project > Properties > Configuration Properties > Debugging and put the IP of HoloLens® inside Machine Name field
6. Run

**HoloLens®**
- Turn on Developer Mode on your device if not done yet
- Info IP: Settings > Same Wifi as Computer > Properties > IPv4
- Info PIN: Settings > Update > For Developers > Under Device discovery > Pair

<br>
Have fun bringing objects from artworks into your reality and exploring art in a new way ~ Your ARtExplorer Team
<br>
