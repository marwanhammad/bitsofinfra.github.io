---
title: "Automating Zerto VPG Creation with PowerShell"
date: 2025-07-11
tags: ["zerto", "powershell", "automation"]
---
Here's how to automate Zerto VPG creation using PowerShell and Zerto REST API.
```powershell
Connect-Zerto -Server zvm.example.com
New-ZertoVPG -Name "Production VMs" -VMs $vmList -TargetSite "DRSite01"
```
