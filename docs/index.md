---
title: Home
summary: Build a quick and dirty image for Windows 365
authors:
    - Aaron Parker
---
Build a quick and dirty image for Windows 365.

## Quick install

Running the following script on a virtual machine deployed into Azure, will install and configure the following items:

* Configure the default profile
* Microsoft Visual C++ Redistributables
* Microsoft FSLogix Apps Agent
* Microsoft Edge
* Microsoft 365 APps
* Microsoft Teams
* Microsoft OneDrive
* Adobe Acrobat Reader DC
* Microsoft VDI optimisations

## Steps

1. First, ensure that you are using a PowerShell as an administrator. Find PowerShell in the Start menu, right-click on the shortcut and choose `Run as Administrator`
2. Install with PowerShell - copy the following command:

```powershell
Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://raw.githubusercontent.com/aaronparker/w365/main/Install-Apps.ps1'))
```

3. Paste the code into the PowerShell prompt that you have chosen to run as administrator
4. Wait a few seconds for the command to run. If the script does not produce any errors, then items listed above should be installed.
