# Computer-Network-for-a-Seven-Floor-Building-Using-Hybrid-Topology
Computer Networking Lab Project using Cisco Packet Tracer. Implements RIP routing with 2911 routers, 2960 switches, and various topologies(Ring, Star, Mesh). Includes subnetting, IP addressing, and inter-PC communication testing.
🏢 Physical Scenario Creation
Floors 1-3: Implemented Ring Topology for balanced load distribution and redundancy.

Floors 4-5: Implemented Star Topology for ease of management and improved performance.

Floors 6-7: Implemented Mesh Topology for high reliability and fault tolerance.

Connectivity: Each floor is connected via a core switch and router to ensure seamless communication.

🌐 IP Addressing Scheme
Following the classful addressing scheme:

Floors 1-3: Class B private IPv4 (172.16.0.0/16)

Floor 1: 172.16.1.1/24

Floor 2: 172.17.1.1/24

Floor 3: 172.18.1.1/24

Floors 4-5: Class C private IPv4 (192.168.0.0/24)

Floor 4: 192.168.1.0/24

Floor 5: 192.168.2.0/24

Floors 6-7: Class A public IPv4 (10.0.0.0/8)

Floor 6: 23.1.0.1/24

Floor 7: 24.1.0.1/24

Default Gateway: Each floor has a dedicated router interface for managing inter-floor traffic.

📡 Routing Protocol
Routing Approach: Dynamic Routing

Protocol Used: OSPF (Open Shortest Path First)

Chosen for its scalability, fast convergence, and efficiency in large networks.

Multi-area OSPF is implemented for better performance.

Network Devices:

Core Routers: Connect inter-floor communication.

Switches: Layer 3 switches for segmentation and efficient data handling.

Access Points: Wireless connectivity for mobility.

🖥️ Inter-PC Communication Testing
ICMP (Ping) Testing: Ensured connectivity between floors.

Traceroute: Verified the routing paths.

Load Testing: Evaluated network performance under heavy traffic.

📷 Snapshots
Network topology diagrams.

Configuration snapshots from routers and switches.

Connectivity test results.

📬 About Me
.Project By: Maddela Nissi Grace
.Contact: nissigracemaddela@gmail.com


📑 Purpose of the Project
Design an optimized network with different topologies for performance and reliability.

Implement efficient IP allocation strategies.

Ensure seamless inter-floor communication using dynamic routing.

Enhance the organization’s scalability and fault tolerance.

🚀 Innovations in the Project
Hybrid Topology: Combining ring, star, and mesh topologies for maximum efficiency.

Multi-Area OSPF: Dividing the network into multiple areas for better management.

Load Balancing: Implementing equal-cost multi-path (ECMP) routing to optimize data flow.

Security Measures: VLANs and ACLs for enhanced security.

📤 GitHub Upload and Engagement Analysis
The project will be uploaded on GitHub for transparency and community contribution.

Engagement will be monitored via views, forks, and issues raised by the community.
