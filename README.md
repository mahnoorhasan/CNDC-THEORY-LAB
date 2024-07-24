# CNDC-THEORY-LAB
Scenario
You have to design and implement networking infrastructure for SZABIST Karachi campus. In
Karachi there are multiple departments functioning in seven different buildings. Based on the
following description, draw up a detailed diagram to illustrate the SZABIST’s networking
infrastructure. In the diagram, include the internal network with the connecting devices. Requirement
for each building have been mentioned and should be implemented accordingly. Clearly label all the
elements of the diagram.
100 Campus Building:
• There are seven labs in 100 building with following number of devices:
o CS Lab have 58 PCs, 2 Printer and 1 ftp server.
o AI Lab has48 PCs and 1 Printer
o Lab-3 have 38 PCs, 2 Printer and 1 ftp server.
o Lab-4 have 35 PCs and 2 Printer.
o Lab-5 have 35 PCs, 2 Printer and 1ftp server.
o Lab-6 have 35 PCs only
o Smart Lab has 40 PCs and 1 Printer.
o Gaming Lab have 9 PCs and 2 Printer.
• There are 20 classrooms in 100-building, each class room has one PC.
• There are around 25 PCs and 4 printers belong to faculty.
• There are 5 PCs and three printers belong to Academic department.
• There are four PCs belong to ADMINISTRATION department.
• There are ten PCs and two printers belongs to IT department.
99 Campus Building:
• There are 18 classrooms in 99-building, each class room has one PC.
• There are around 32 PCs belong to faculty and 6 printers.
• There are six PCs and two printers belong to Academic department.
• There are four PCs and one printer belongs to IT department.
• There are 12 PCs and 4 printers belong to EXAMINATION department.
• There are two PCs belong to ADMINISTRATION department.
• There are four servers in data center, one for web server, one for ZABDESK, one for email and one
for CMS.
• EDGE router is located at 99-Campus Building.

General Guidelines:
• Use VLSM to subnet IP pools (minimum wastage of IPs)
• Use IP pool XX.XX.XX.XX/24. Replace xx with your roll number. you have four IP pools as
project group have four members. e.g. 221.21.14.0/24. If you need more IPs then use private IP
pools. e.g. 192.168.1.0/24.
• Make VLANs for each department for better network management or where necessary.
• Implement Inter-VLAN routing where necessary.
• Assign IP addresses to each PCs should be through DHCP in SZABIST Karachi Campus.
• If you have designed switched network, Configure DHCP server on your EDGE router, otherwise you
have to configure DHCP server on154-Campus’s router.
• Statically assign IP addresses to the SERVER and the printers in SZABIST Karachi.
• Port security must be enabled for each Servers and for the LAB devices in SZABIST Karachi campus.
Use any type of port security.
• NAT should be enabled on your edge router to connect SZABIST’s network with the internet. Use
11.11.11.0/30 as public IP pool between EDGE and ISP routers.
• No other department can access Faculty’s Printers (Implement it using ACL).
• Only Faculty and Labs PCs can access ZABDESK (Implement it using ACL).
• If you need to implement dynamic routing, use single area OSPF for routing.
• Every PC, Server and Printer in all branches should be reachable to each other, Except any restriction
mentioned above
• Remote management of Routers through any device.
• Switches must be accessible remotely from anywhere in SZABIST
• Switches and routers must be password protected (console, Telnet and privileged mode)
• Topology properly labeled. Necessary information like Subnets, Vlans, Network IP, port numbers,
device IP and devices name (hostname) must be properly visible and configured.
