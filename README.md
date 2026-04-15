Enterprise Network Design Project
📌 Overview

This project demonstrates the design and implementation of a scalable, secure, and highly available enterprise network for a Trading Floor Support Centre with 600 users.

The network is built using Cisco Packet Tracer and follows a hierarchical architecture (Core, Distribution, Access layers) to ensure performance, redundancy, and future scalability.

🏗️ Network Architecture
Hierarchical Design (Core, Distribution, Access)
Dual ISP connectivity for redundancy
Multilayer switches for inter-VLAN routing
Access switches for end-user connectivity
🖼️ Project Screenshots
🔹 Network Topology

🔹 VLAN Configuration

🔹 OSPF Routing

🔹 NAT Configuration

🔹 Port Security

📌 Note: Create an images/ folder in your repo and upload screenshots from Packet Tracer.

🚀 Key Features
✅ VLAN-based network segmentation
✅ Inter-VLAN routing using multilayer switches
✅ OSPF dynamic routing protocol
✅ Dual ISP redundancy
✅ DHCP for automatic IP allocation
✅ NAT (PAT) for internet access
✅ SSH for secure remote access
✅ ACLs for traffic filtering
✅ Port Security (Sticky MAC + Shutdown mode)
✅ Wireless networks for each department
🏢 Department VLANs
Department	VLAN	Subnet
Sales & Marketing	10	172.16.10.0/24
HR & Logistics	20	172.16.20.0/24
Finance	30	172.16.30.0/24
Admin & PR	40	172.16.40.0/24
ICT	50	172.16.50.0/24
⚙️ Technologies Used
Cisco Packet Tracer
VLAN (Virtual LAN)
OSPF Routing
NAT (PAT)
DHCP
ACL (Access Control List)
Port Security
SSH
🔐 Security Features
Port Security (Max 2 MAC, Sticky, Shutdown mode)
SSH-based secure login
ACL rules for traffic control
VLAN isolation
📊 Testing & Results
✔ Same VLAN communication successful
✔ Inter-VLAN routing working
✔ Internet access via NAT successful
✔ Redundancy working (failover tested)
✔ Unauthorized devices blocked
🛠️ How to Run
Open Cisco Packet Tracer
Load .pkt file
Start simulation mode

Test connectivity using:

ping 172.16.x.x
ping 8.8.8.8

Verify using:

show ip route
show vlan brief
📂 Project Structure
📁 Enterprise-Network-Project
 ├── 📁 images/
 ├── 📄 network.pkt
 ├── 📄 README.md
📈 Future Improvements
Cloud integration
IPv6 implementation
Advanced firewall security
Network automation (SDN)
👨‍💻 Author

Your Name
📧 your-email@example.com

⭐ If you like this project

Give it a ⭐ on GitHub!

⚠️ Next Step (IMPORTANT)

👉 Upload screenshots like:

Topology (full network)
VLAN config
OSPF routing table
NAT config
Port security test
<img width="975" height="548" alt="image" src="https://github.com/user-attachments/assets/545c9da9-9c25-44d4-af24-29b31bc3d996" />
<img width="975" height="548" alt="image" src="https://github.com/user-attachments/assets/45208a11-e6e8-4a43-a515-314ba2ee1a28" />

