<img width="1700" height="148" alt="image" src="https://github.com/user-attachments/assets/b3d2827b-8b59-4d45-b865-204643d697c1" />




<img src="report_16075921.gif" width="150">

<b>Overview</b>
<br />
<br />
  This lab involved designing and physically building a small network in an in-person classroom environment. The goal was to understand core networking concepts, device configuration, and basic security considerations. The goal was to configure a router, switch, and 2 PCs to support both IPv4 and IPv6 connectivity. As well as configuring SSH security on the Router and traditional Telnet on the Switch. While testing and documenting the network using common CLI commands. 
<br />
<br />
<br />
<br />

<img src="dartboard_14357078.gif" width="150">

<b>Objectives</b>
<br />
- Construct the topology: PC-A, Router, Switch, PC-B, DTE/DCE ethernet cables
- Develop the IPv4 Addressing Scheme
- Configure IPv4 and Security Settings
- Power Cycle All Devices
- Test and Verify IPv4 End-to-End Connectivity
- Configure IPv6 Addressing on Router
- Test and Verify IPv6 End-to-End Connectivity
<br />
<br />
<br />


<img src="exchange_17110512.gif" width="150">

<b>Tools & Equipment</b>
- Cisco 1941 Router
- Cisco 2960 Switch
- Cisco Router CLI
- Cisco Switch CLI
- SSH & Telnet
- IPv4 & IPv6
- Windows Command Prompt
<br />
<br />
<br />
<br />


<b>Network Topology</b>
<br />
<br />
<img width="609" height="137" alt="image" src="https://github.com/user-attachments/assets/77b5680d-ada1-4228-8daf-63d9efe7c65f" />
<br />
<br />
<br />
<br />


<img src="gear_18998345.gif" width="150">

<b>Key Configurations Performed</b>
<br />
- IPv4 Addressing
  - Designed an IPv4 addressing scheme using <b>192.168.0.0/24</b>
  - Subnetted the network to support:
    - Subnet A (30 hosts)
    - Subnet B (126 hosts)
  - Assigned IP addresses to router interfaces, switch SVI, and hosts

- IPv6 Configuration
  - Configured IPv6 addressing using <b>2001:DB8:ACAD::/48</b>
  - Enabled IPv6 unicast routing
  - Implemented SLAAC for automatic host addressing
  - Configured link-local addresses <b>(FE80::1)</b>
  <br />
  <br />


<img src="personal-data_19002109.gif" width="150">

<b>Security Configurations</b>
<br />
- Configured SSH-only access on the router
- Created local administrative user credentials
- Disabled DNS lookup
- Encrypted passwords and configured MOTD banner
- Configured Telnet access on the switch
- Secured console and VTY lines
<br />
<br />



<img src="communications_14164989.gif" width="150">

<b>Testing & Verification</b>
<br />
- Verified IPv4 connectivity using ping between all devices
- Verified IPv6 connectivity between hosts and router interfaces
- Power-cycled devices to confirm configuration persistence
- Used CLI commands to validate configurations
<br />
<br />


<img src="invention_18996943.gif" width="150">

<b>What I Learned</b>
<br />
- How to design and subnet a network based on host requirements
- The difference between IPv4 and IPv6 configuration workflows
- How to secure network infrastructure using SSH
- How to troubleshoot connectivity issues in a simulated environment
- Why proper documentation and verification are critical in networking











