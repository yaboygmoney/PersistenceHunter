# PersistenceHunter

This tool is an effort to automate checking many of the common registry and filepath locations associated with Windows persistence mechanisms identified in the MITRE ATT&CK Matrix. It has been designed with the presumption that no foreign executables (i.e. Autoruns.exe) may be brought into the environment. It also assumes there is little to no historical data of value, providing a point in time analysis.

## Usage
```powershell
PS> Import-Module ./PersistenceHunter.ps1
```

## Covered Techniques
+ AppCert DLLs
+ AppInit DLLs
+ Application Shimming
+ Authentication Packages (LSA)
+ BITS Jobs
+ Chrome Extensions
+ Firefox Extensions
+ Hidden Files
+ Hidden Directories
+ Image File Execution Options
+ Logon Scripts
+ Scheduled Tasks
+ Security Support Providers
+ Services
+ SIP and Trust Provider Hijacking

## To-do 
##### Some of these won't be able to be done with PowerShell
+ Bootkits
+ Change Default File Association
+ Component Firmware
+ COM Hijacking
+ DLL Search Order Hijacking
+ External Remote Services
+ File System Permissions Weakness
+ Hooking
+ Hypervisor
+ LSASS Driver
+ Modifying Existing Service
+ Netsh Helper DLL
+ Office Application Startup
+ Path Interception
+ Port Monitors
+ PowerShell Profile
+ Redundant Access
+ Registry Run Keys / Startup Folder
+ Screensaver
+ Server Software Component
+ Service Registry Permissions Weakness
+ Shortcut Modification
+ System Firmware
+ Time Providers
+ Valid Accounts
+ Web Shell
+ Windows Management Instrumentation Event Subscription
+ Winlogon Helper DLL
