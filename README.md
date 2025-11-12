# VMware-workstation-on-windows-settings
```
bcdedit /set hypervisorlaunchtype off
```
```
dism.exe /Online /Disable-Feature:Microsoft-Hyper-V-All
dism.exe /Online /Disable-Feature:VirtualMachinePlatform
dism.exe /Online /Disable-Feature:WindowsHypervisorPlatform
dism.exe /Online /Disable-Feature:WindowsSubsystemForLinux
```
