# SIEM Basics with Azure Sentinel: Hands-On with Live Cyber Attacks

This project demonstrates the setup and configuration of Azure Sentinel as a Security Information and Event Management (SIEM) system. It involves configuring a virtual machine as a honeypot to capture and monitor live attacks, specifically RDP brute force attempts, from around the globe.

## Project Overview

In this project, I have:
- **Configured Azure Sentinel**: Set up as the central SIEM tool to monitor and manage security events.
- **Deployed a Virtual Machine Honeypot**: Actively captures live RDP brute force attacks.
- **Implemented a Custom PowerShell Script**: Retrieves geolocation information of attackers based on their IP addresses and plots this data on the Azure Sentinel Map.

## Key Features

- **Real-Time Attack Monitoring**: Observe live RDP brute force attacks from various geographical locations.
- **Geolocation Mapping**: Visual representation of attack origins on Azure Sentinel’s built-in map, providing insight into global threat distribution.
- **Custom PowerShell Script**: Automates the process of geolocating IP addresses and integrating the data into Azure Sentinel.

## Files Included

- **SIEM Basics with Azure-Sentinel.pdf**: Configuration steps for Azure Sentinel and the virtual machine honeypot.
- **Custom_Security_Log_Exporter.ps1**: The custom PowerShell script used for geolocation lookup and mapping.

## Requirements

- An active Azure subscription.
- Basic understanding of Azure Sentinel and PowerShell scripting.
- A virtual machine to act as a honeypot.

## How to Use

1. **Setup Azure Sentinel**: Follow the instructions in `SIEM Basics with Azure-Sentinel.pdf` to set up and configure Azure Sentinel.
2. **Deploy the Honeypot**: Use the provided setup instructions to deploy a virtual machine as a honeypot.
3. **Run the PowerShell Script**: Execute `Custom_Security_Log_Exporter.ps1` to start mapping attackers' geolocation data on the Azure Sentinel Map.

## Screenshots

<p align="center">
  <img src="screenshots/azure-sentinel-dashboard.png" alt="Azure Sentinel Dashboard" width="400"/>
  <br/><i>Azure Sentinel Dashboard with attack data.</i>
</p>

<p align="center">
  <img src="screenshots/honeypot-setup.png" alt="Honeypot Setup" width="400"/>
  <br/><i>Deployment of the virtual machine honeypot.</i>
</p>

<p align="center">
  <img src="screenshots/geolocation-map.png" alt="Geolocation Map" width="400"/>
  <br/><i>Geolocation mapping of RDP brute force attacks.</i>
</p>

## Contact

Maryam Fatima  
GitHub Profile: [MaryamFatima16](https://github.com/MaryamFatima16)  
LinkedIn Profile: [Maryam Fatima](https://linkedin.com/in/maryam-fatima03)  
Email: [your-email@example.com](maryamfatima03@gmail.com)
