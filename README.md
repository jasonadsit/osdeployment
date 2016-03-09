# A Collection of Tips and Tricks for Operating System Deployment, MDT, Hyper-V, etc.

## VMware and Hyper-V on the Same Laptop

bcdedit /copy "{current}" /d "Hyper-V"

bcdedit /set "{current}" hypervisorlaunchtype off
