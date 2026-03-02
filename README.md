# Technical-Foundation-DBA-to-Network-Security
From Database Administration to Network Security Architecture A Structured Technical Learning Journey Supporting My Data Analytics Career

---

## 📌 Introduction

This repository documents my structured progression from **Database Administration (DBA)** to **Networking Fundamentals** and ultimately to **Enterprise Security Architecture Design**.

Rather than studying isolated technical topics, I developed an understanding of the **full data lifecycle**:

- How data is structured and governed (DBA)
- How data travels across networks (TCP/IP)
- How data is analyzed at packet level (Wireshark)
- How data environments are secured (VLAN segmentation, VPN, firewall design)
- How data availability is maintained (backup and disaster recovery planning)

This technical foundation strengthens my ability to operate as a Data Analyst with infrastructure awareness and security consciousness.

---

# 🗄️ Phase 1 — Database Administration (DBA Foundation)

## Core Areas of Exposure

- Relational database design
- Entity-Relationship (ER) modeling
- Primary & foreign key relationships
- Normalization (1NF, 2NF, 3NF)
- SQL querying and filtering
- Indexing concepts
- Data integrity enforcement
- Role-based access control (RBAC)
- Backup and recovery strategies

---

## 🔍 Key DBA Concepts Learned

### 1️⃣ Data Integrity

- Enforcing primary keys to prevent duplication
- Using foreign keys to preserve relational consistency
- Applying `NOT NULL` and `UNIQUE` constraints
- Preventing update and deletion anomalies

Understanding this ensures reliable datasets — critical in analytics pipelines.

---

### 2️⃣ Database Normalization

Reducing redundancy and improving performance through:

- **First Normal Form (1NF):** Atomic values
- **Second Normal Form (2NF):** Full functional dependency
- **Third Normal Form (3NF):** No transitive dependencies

Normalization improves query performance and ensures clean analytical reporting.

---

### 3️⃣ Role-Based Access Control (RBAC)

Limiting database access based on user roles:

- Database Administrators
- Analysts (read-only access)
- Application roles
- Limited privilege users

This concept directly connects to later enterprise security planning.

---

### 4️⃣ Backup & Recovery Awareness

- Full backups
- Incremental backups
- Restore procedures
- Data recovery planning

This foundation later expanded into full disaster recovery planning during the networking and security phase.

---

# 🌐 Phase 2 — Networking Fundamentals

Transition from:

**“Where data lives” → “How data travels.”**

---

## 📚 Concepts Covered

- OSI Model vs TCP/IP Model
- Ethernet frames and MAC addressing
- IPv4 addressing and subnetting
- IPv6 awareness
- DNS resolution
- Routing fundamentals
- LAN vs WAN vs MAN comparison
- Subnet planning
- VLAN segmentation

---

## 🖥️ Real Diagnostics Performed

Commands used:

- `ipconfig`
- `tracert`
- `nslookup`

From these, I interpreted:

- Private IP ranges (192.168.x.x)
- Default gateways
- DHCP lease assignments
- WAN routing hops
- DNS alias resolution

This provided infrastructure-level awareness often missing in entry-level data roles.

---

# 🔬 Phase 3 — Packet-Level Analysis with Wireshark

Using Wireshark, I analyzed real TCP and HTTP traffic to understand communication at the transport layer.

---

## 🧠 TCP 3-Way Handshake Analysis

Observed connection sequence:

1. Client → Server: **SYN**
2. Server → Client: **SYN-ACK**
3. Client → Server: **ACK**

Only after this handshake does HTTP data transmission begin.



---

## 🔎 Key Observations from Capture

- Client IP: `145.254.160.237`
- Server IP: `65.208.228.223`
- Client Port: `3372` (ephemeral port)
- Server Port: `80` (HTTP)
- TCP Header Length: 28 bytes (including options)
- MSS and SACK options enabled

This demonstrates understanding beyond application layer into protocol-level analysis.

---

## 📸 Wireshark TCP Capture

![Wireshark TCP Capture](Image/wireshark_tcp_handshake.png)

This capture demonstrates understanding of transport-layer communication beyond application-level visibility.

---

# 🏢 Phase 4 — Enterprise Network & Security Architecture

Culmination of the course: designing a secure small business network model.

---

## 🔐 Network Design Overview

Components included:

- ISP Internet Connection
- Firewall Router (NAT + VPN enabled)
- Managed Switch (VLAN configured)
- VLAN 10 — Internal Network (192.168.10.0/24)
- VLAN 20 — Guest Network (192.168.20.0/24)
- NAS Backup Server
- Microsoft 365 Cloud Integration
- Encrypted VPN Remote Access
- IDS/IPS Controls
- Security Policy Documentation

---

## 🔹 VLAN Segmentation

Internal business traffic is separated from guest WiFi using VLAN configuration.

This limits lateral movement during a breach and protects sensitive systems.

---

## 🔹 VPN Remote Access

Remote employee access configured via:

- Encrypted VPN tunnel
- Firewall-terminated authentication
- Secure remote communication

Critical for modern distributed work environments.

---

## 🔹 Backup & Disaster Recovery Planning

- Daily NAS backups
- Offsite cloud redundancy
- Incident response documentation
- Disaster recovery procedures
- Employee security awareness training

This extended earlier DBA backup awareness into full enterprise governance.

---

## 📸 Final Secure VLAN Network Diagram

![Secure VLAN Network Architecture](Image/vlan_network_diagram.png)

This architecture demonstrates:

- Network segmentation
- Lateral movement prevention
- Secure remote access
- Cloud service integration
- Backup governance awareness

---

# 🛡️ Security Governance Exposure

Beyond configuration:

- Password policy design
- Administrative responsibility planning
- User security education
- Threat awareness training
- Incident notification procedures
- Business continuity planning

This bridges technical implementation and policy governance.

---

# 📈 Key Competencies Developed

- Systems-level thinking
- Infrastructure awareness
- Network segmentation design
- TCP/IP protocol analysis
- Security risk assessment
- Cloud integration modeling
- Backup governance
- Disaster recovery strategy
- Technical documentation skills

---

# 🎯 How This Strengthens My Data Analytics Career

As a Data Analyst, I now understand:

- How datasets travel across networks
- How infrastructure impacts availability
- How segmentation protects sensitive analytics systems
- Why VPN security matters in remote data access
- How backup strategy preserves analytical integrity
- How governance frameworks ensure compliance

This cross-domain exposure enhances my ability to collaborate with:

- IT infrastructure teams
- Security teams
- Database administrators
- Cloud architects

It positions me as a technically aware analytics professional — not just a tool user.

---

# 🏁 Conclusion

This journey from **DBA → Networking → Security Architecture** represents layered exposure to:

- Data structure
- Data transport
- Data protection
- Data governance

This foundation supports my long-term goal of operating as a data professional with infrastructure intelligence and security awareness.

---
