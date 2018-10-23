---
layout: default
---

# Creating a New Virtual Machine on Proxmox

- Click "Create VM" (top right corner)
    - General
        - Name: *YourLastName* + *OS/TypeofVM*
        - Resource Pool: Playground
        - VMID: Increment this number until finding a valid ID
    - OS
        - Select the appropriate OS type
    - CD/DVD
        - ISO - You need to select the requisite installation file
    - Hard Disk
        - Leave as default
    - CPU
        - Leave as Default
    - Memory
        - Leave as default
    - Network
        - Under Bridge Mode, select Bridge: vmbr1
        - Check Firefall
    - Confirm/Finish
        - Note: If many people are creating VM's at the same time you may get an error that the VMID you selected is no longer valid. Either go back and increment further, or if this is during a meeting let us know and we will arbitrate ID numbers
- Starting Your VM
    - Find and click your VM in the big list under "Playground"
    - Click Start
    - Click Console