# Hyper-V: 
## Definition: 
* Hyper-V formerly known as Windows Server Virtualication is a native hypervisor. It can create virtual machines on x86-64 systems running Windows.
## Usage: 
* To run Docker deamon, must enable **Hyper-V**. 
## Manage Hyper-V: 
Must open Windows PowerShell to manage **Hyper-V**: 
* Turn off: **bcdedit /set hypervisorlaunchtype off**. 
* Turn on: **bcdedit /set hypervisorlaunchtype on** or **bcdedit /set hypervisorlaunchtype auto**.

After running one of those commands, must restart the computer to complete the operation. 