# A Collection of Tips and Tricks for Operating System Deployment, MDT, Hyper-V, etc.

bcdedit /copy "{current}" /d "Hyper-V"

bcdedit /set "{current}" hypervisorlaunchtype off
