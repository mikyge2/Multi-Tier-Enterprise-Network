# Multi-Tier-Enterprise-Network
# Network Topology: Partial Mesh
The decision to opt for a partial mesh topology over other network topologies is driven
by several practical considerations tailored to organizational needs. The partial mesh
topology was chosen for its balance between redundancy, scalability, and cost-
effectiveness. By selectively establishing direct connections between critical sites, such
as the main site, regional office, manufacturing facility, distribution center, and remote
site, we ensure efficient and reliable communication pathways where they are most
essential.
This topology allows us to prioritize direct connectivity where it is most needed,
facilitating seamless data exchange, collaboration, and resource sharing between key
sites while avoiding unnecessary complexities and overhead associated with a full mesh
topology.
Additionally, the partial mesh design offers flexibility for future expansion, enabling the
network to grow and adapt to evolving requirements without compromising performance
or manageability. Overall, the partial mesh topology aligns closely with our
organization's connectivity needs, providing a robust and scalable network infrastructure
tailored to our specific operational demands.
# Topology Structure:
The Main Site has direct connections to the Regional Office, Manufacturing Facility, and
Distribution Center.
The Regional Office has direct connections to the Main Site, Distribution Center, and
Remote Site.
The Manufacturing Facility has a direct connection to the Main Site and Distribution
Center.
The Distribution Center has direct connections to the Main Site, Regional Office, and
Remote Site.
The Remote Site has direct connections to the Regional Office and Distribution Center.
This topology ensures that each site has direct communication links to the necessary
sites as per requirements.
# Naming Conventions
• Routers – Site + (RouterID)
Multi Layer Switches – Site + Multi Layer Switch (ML-SwithID)
• Switch – Department (SwitchID)
• PC – Department + Site+PCID
• Access Point - Department+Site+Access Point
SSID – Department+Site+AP
Password - “AP-cs461”
• Laptop - Department+Site+LaptopID
• Printer - Department+Site+Printer
# Technologies Implemented
1. VLAN: Virtual Local Area Network to divide each department with in a site.
2. Inter-VLANing to enable communication between different VLANs (different departments).
3. Subnetting: Partitioning network to smaller networks.
4. OSPF Routing: Open Shortest Path First Routing on routers to route traffic.
5. DHCP: Dynamic Host Configuration Protocol hosted on a server to dynamically allocate IP
address to all end devices.
6. DNS: Domain Name System that translate domain name to IP address.
7. HTTPS: Hypertext Transfer Protocol Secure used to access the simple hosted website.
8. NAT (PAT): Network Address Translation (Port Address Translation) used to assigne different
public IP address to end devices when accessing external network.
9. ACL: Access Control List a list implements to permit communication and translation by PAT
