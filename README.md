# Active Directory Setup

## 00 - Install VMs
1. Installed WinServer 2022 as a VM in VMWare workstation
2. Installed Windows 11 as a Workstation

## 01 - Install DC
1. use `sconfig` to:
    - Change the hostname
    - Change IP Address to static
    - Change the DNS server to our own IP Address
2. Install the Active Directory Windows Feature


```powershell
Install-WindowsFeature AD-Domain-Services -IncludeManagementTools
```

