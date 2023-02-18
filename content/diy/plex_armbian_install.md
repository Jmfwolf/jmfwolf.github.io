---
title: "Plex Media Server Armbian Install"
date: 2023-02-18
publishdate: 2023-02-19
tags: ["DIY", "self-hosted", "Armbian", "plex media server"]
comments: false
---
Armbian is a Debian-based operating system designed for ARM-based devices. It is an excellent choice for those who want to run a lightweight and efficient operating system on their single-board computer or other ARM-based devices. One of the many benefits of Armbian is its flexibility, as it allows users to install a wide range of software packages. In this article, we'll walk you through the steps to install Plex Media Server on Armbian using the Armbian Config.

Step 1: Install Armbian
The first step in installing Plex Media Server on Armbian is to install Armbian on your single-board computer. Visit the Armbian website and download the appropriate image for your device. Flash the image onto a memory device using a tool like Balena Etcher. Insert the memory device into your device and boot it up.

Step 2: Access the Armbian Config
Once Armbian is up and running on your device, you can access the Armbian Config by typing the following command in the terminal:

```sh
sudo armbian-config
```
Step 3: Select Plex Media Server
In the Armbian Config, select "Software" and then "Plex Media Server." The Armbian Config will download and install the necessary packages for Plex Media Server.

Step 4: Configure Plex Media Server
Once Plex Media Server is installed, you can configure it by accessing the web interface. Open a web browser and enter the IP address of your device followed by ":32400/web" (e.g. 192.168.1.100:32400/web). This will take you to the Plex Media Server setup wizard. Follow the prompts to configure Plex Media Server to your liking.

Step 5: Enjoy Your Media Library
Once you have finished configuring Plex Media Server, you can start adding media to your library. Simply add your media files to the appropriate folder on your device, and Plex Media Server will automatically detect and organize them. You can then access your media library from any device with the Plex app installed.

In conclusion, Armbian is a flexible and lightweight operating system that is ideal for running on single-board computers and other ARM-based devices. Installing Plex Media Server on Armbian using the Armbian Config is a simple and straightforward process. Once installed, Plex Media Server provides a powerful and flexible media streaming platform. Armbian can be used for a wide range of use cases, including media centers, network-attached storage, and more. With Armbian, the possibilities are endless.