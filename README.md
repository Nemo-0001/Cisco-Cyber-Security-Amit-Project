# **School Network Security Architecture**

## **Project Overview**

This project involves designing a comprehensive **network architecture** for a large multinational school that has two buildings on campus. The objective is to ensure a secure, scalable, and functional network, complete with a published website and necessary security measures. The project is divided into three main phases, each focusing on different aspects of the network configuration and security implementation.

---

## **Project Phases**

### **Phase 1: Network Topology & IP Scheme**
In the first phase, the main task is to design the **network topology** and implement an effective **IP addressing scheme**.

- **Network Topology:**
  - Design a network containing essential devices such as **switches**, **routers**, **access points**, and **end devices**.
  - Ensure that the devices are strategically placed in the two school buildings to provide efficient connectivity.

- **IP Addressing Scheme:**
  - Implement a detailed IP addressing plan, including the creation of **subnets**.
  - Define at least **three VLANs** per building to segment the traffic for different departments: **Teachers**, **HR**, and **Operations**.

### **Phase 2: Network Configuration**
In the second phase, the network devices are configured with various protocols and settings to ensure proper routing, server configuration, and security.

- **Inter-VLAN and OSPF Configuration:**
  - **OSPF (Open Shortest Path First)** is used for routing between subnets, allowing dynamic updates and flexibility as the network grows.
  - **Inter-VLAN routing** is implemented to ensure communication between different VLANs.

- **Web Server Setup:**
  - A **web server** is configured to host the school’s website, and a public IP is assigned to allow access from outside the network.
  - **NAT (Network Address Translation)** is configured to translate internal IP addresses to the public IP, enabling internet access for internal devices.

- **DNS Configuration:**
  - A **DNS server** is set up to resolve domain names to IP addresses, ensuring proper communication within and outside the network.

- **Security Measures:**
  - Implement **Port Security** on switches to prevent unauthorized devices from connecting to the network.
  - Configure a **NTP (Network Time Protocol) server** to synchronize time across all network devices.
  - Set up a **Syslog server** for logging and monitoring network events.
  - Use **ACLs (Access Control Lists)** to restrict access to the web server and other critical resources.

### **Phase 3: Testing & Presentation**
In the final phase, the network configuration is tested thoroughly, and a presentation is prepared to document the entire setup and recommendations for future improvements.

- **Connectivity Testing:**
  - Use **ping** and **traceroute** commands to test network connectivity and troubleshoot any issues that arise.
  - Ensure that all VLANs can communicate with each other and that devices can access the internet via NAT.

- **Security Validation:**
  - Test the **ACLs** to confirm that only authorized traffic is allowed to access the web server.
  - Monitor the network logs through the Syslog server to detect potential threats.

- **Presentation:**
  - Prepare a comprehensive presentation explaining the network design, IP scheme, and security measures.
  - Include recommendations for defending against common network attacks such as **ransomware** and **social engineering**.

---

## **Technology Stack**

- **Cisco Packet Tracer**: Used to design and simulate the network topology.
- **OSPF**: Dynamic routing protocol for efficient traffic management.
- **NAT**: Ensures internal devices can access the internet securely.
- **ACLs**: Enhance security by controlling network traffic based on IP addresses and protocols.
- **Port Security**: Prevent unauthorized devices from connecting to the network.
- **Syslog Server**: Centralized logging for network event monitoring.
- **DNS**: Domain Name System for translating domain names to IP addresses.
- **NTP**: Network Time Protocol for time synchronization across devices.

---

## **How to Run the Project**

1. **Download Cisco Packet Tracer**: You can simulate the project using **Cisco Packet Tracer**. Download it from [here](https://www.netacad.com/courses/packet-tracer).

2. **Import the Project File**: Load the project file into **Cisco Packet Tracer** to view and modify the network design.

3. **Test Connectivity**: Use the built-in testing tools like **ping** and **traceroute** to ensure all devices are connected properly and the configuration works as expected.

4. **Modify Configuration**: Adjust the **VLAN**, **OSPF**, **NAT**, and **ACL** settings as needed to suit specific needs.

---

## **Project Structure**

- **/network_topology/**: Contains the design diagrams and network layout.
- **/configurations/**: Stores the configuration files for routers, switches, and servers.
- **/presentation/**: Includes the presentation slides that document the design process and recommendations.
- **/testing/**: Contains test results for connectivity and security validation.
- **/scripts/**: Holds the scripts for setting up the network (e.g., ACLs, NAT, OSPF).

---

## **Future Enhancements**

- Implement **firewalls** to provide an additional layer of security for the school’s network.
- Introduce **VPN (Virtual Private Network)** for secure remote access by staff and students.
- Use **Intrusion Detection Systems (IDS)** to detect and prevent potential attacks.
- Explore **Cloud Integration** for hosting the school's website and critical services on the cloud to improve scalability.

---

## **Contributors**

- **[Ziad Bassem]**
- **[Ahmed Yasser]**
- **[Habiba Ahmed]**
- **[Shaimaa Elkastamony]**
- **[Salma Ismail]**
