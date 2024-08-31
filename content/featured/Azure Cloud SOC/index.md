---
date: '1'
title: 'Azure Cloud SOC'
cover: './Azure.gif'
github: 'https://github.com/JohnSomanza/Cloud-SOC-Honeynet'
external: 'https://github.com/JohnSomanza/Cloud-SOC-Honeynet'
tech:
  - Azure Virtual Machines
  - Microsoft Sentinel (SIEM)
  - Microsoft Defender for Cloud
  - Log Analytics
  - Network Security Groups
---

In this project, I established a mini honeynet within Azure and aggregated log data from various sources into a Log Analytics workspace. Microsoft Sentinel utilized this data to develop attack maps, trigger alerts, and generate incident reports. I initially assessed security metrics in an unsecured environment over a 24-hour period. Following the implementation of security controls to strengthen the environment, I conducted a subsequent 24-hour assessment of the metrics. The findings are detailed below.
