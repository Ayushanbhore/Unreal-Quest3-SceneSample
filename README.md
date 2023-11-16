

# Unreal Quest 3 Scene Sample

Welcome to the Unreal Quest 3 Scene Sample project! This repository provides a complete example of how to create a passthrough experience in Unreal Engine for the Oculus Quest 3 and introduces a unique shader that acts as a real-time occluder, enabling real-life objects to be seamlessly integrated into the virtual environment.

Map out your Space / Highlight Scene Objects / Occlude them in Real Life / Go Crazy

This Project is made on Unreal 5.2.0 OR LATEST ONE, Please use this or newer versions to run this one.

Table of Contents
- [Overview](#overview)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [License](#license)




# Overview

This sample project showcases the integration of Passthrough, Depth API, and Mesh API provided by Oculus for the Meta Quest 3 VR headset within the Unreal Engine 5.1.1 environment. It demonstrates how to access and utilize real-time camera feed (passthrough), depth information, and mesh data to create AR experiences in the Unreal Engine environment for Oculus Quest 3 and also for Oculus Quest Pro


- **Passthrough Experience**: Enjoy a seamless passthrough experience on your Oculus Quest 3. Immerse yourself in a combination of the virtual and real worlds, enhancing your XR experiences.

- **Real-Time Occlusion**: The project includes a custom shader that effectively occludes real-life objects in the scene. This allows for interactions and integration of real-world objects with virtual content, creating a more immersive mixed reality environment.

- **Scene Data Integration**: Use the passthrough data to access and interact with real-world objects. For example, by pressing a button, you can highlight tables or couches in your physical room. The Quest 3's passthrough data is utilized to spawn virtual objects such as meshes or materials.

- **User Interface for Real-Time Manipulation**: A user interface (UI) pops up when you press the menu button. This UI enables you to hide/show real-life tables and make them behave like occluders, seamlessly blending your virtual and physical environment.

- **Masking Real-Life Objects into Virtual Reality**: A new feature allows you to mask real-life objects into virtual reality. This means that real-world objects can be seamlessly integrated into your VR experience, with the ability to cut them from the virtual environment, allowing you to see your VR content along with the masked reality.

# Getting Started

Before using this sample project, make sure you have the following prerequisites installed and set up:

## Prerequisites
- Unreal Engine (version 5.2.0 or later)
- MetaXR Plugin for Unreal Engine (51.0 , 53.0 , 54.0)
- Meta Quest 3 Device or Meta Quest Pro Device
- Meta Developer Account

## Installation

Follow these steps to run the sample project and explore the integration of Passthrough, Depth API, and Mesh API:

1. Clone this repository to your local machine:

``` bash
git clone https://github.com/ayushanbhore/Unreal-Quest3-SceneSample.git
```
2. Open the project in Unreal Engine. Works Best with Unreal Engine 5.2.0 and later

3. Download the MetaXR Plugin for your Engine 
-> Preferably - 54.0 Version
   
``` bash
https://developer.oculus.com/downloads/package/unreal-engine-5-integration
```

4. It is recommended to place the MetaXR Plugin in the Marketplace Folder inside your Unreal Engine Directory

5. Launch Unreal Engine and Make Sure to Tick Meta XR Plugin in the Plugins Section

 -> Please Uncheck Oculus VR Plugin or it may cause issues 
 
   ![](Images/D.png)

7. Copy these settings in the Project Settings -> Plugins -> MetaXR -> Mobile Section of you Unreal Engine
   
  ![](Images/MobileSettings.png)


## Passthrough Build :

Follow my another Repository for Passthrough Setup, Alothough this might also have a passthrough but this one majorly foccuses on Scene Setup.
Please note that you dont need a Quest 3 For Scene API Ready Experiences, Quest Pro and Quest 2 can also work out but for Depth API you definately need a Quest 3.

``` bash
git clone https://github.com/ayushanbhore/Unreal-Quest3-PassthroughSample.git
```

## License
This sample project is licensed under the MIT License. Feel free to modify and distribute it according to the terms of the license. See the [LICENSE](LICENSE) file for more details.


