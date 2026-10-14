# Active Directory Home Lab

## Overview
Built a domain through active directory and established a domain controller on windows server 2019, multiple users, and a client pc on windows 10. Created a domain, a nat/ras server, a dhcp server, and a client pc that is able to join the domain and connect to the internet and internal netwrok. All of this was done through virual machines in virtual box.

## Environment
- Hypervisor: VirtualBox
- Domain Controller: Windows Server [version]
- Client(s): Windows 10/11
- Network: [internal/NAT, IP range]

![Network diagram](diagrams/network-diagram.png)

## Steps Completed
### 1. Created the virtual machines
To create the VMs, I installed oracle virtual box as the hypervisor. I then downloaded windows 2019 server and windows 10 from the internet as ISO files and imported them into virtual box. I set up the domain controller first, which was the windows 2019 server OS, and configured it to have 2 network adapters, one for the internet and one for the internal network. The windows 10 VM I created was designed to be the cleint pc that would join the domain and it was configured with 1 network adapter for the internal network.
![VM setup](screenshots/01-vm-created.png)

### 2. Installed AD DS and promoted the domain controller
...

### 3. Created OUs, users, and groups
...

### 4. Joined a client to the domain
...

## Issues and Fixes
- **Problem:** [what broke]
  **Fix:** [what you did]

## What I Learned
3-4 sentences in your own words.

## Credit
Built following [video title] by [channel name] (link).
