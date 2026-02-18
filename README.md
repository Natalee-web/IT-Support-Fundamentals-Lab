# IT Support Fundamentals: System Audit & Troubleshooting Lab

## 📌 Introduction
As an aspiring IT Support Specialist, my goal is to ensure high system uptime and efficient user support. This project serves as a practical demonstration of my ability to perform **System Audits**, verify **Network Connectivity**, and follow a **Structured Troubleshooting Methodology**. # Course 2: The Bits and Bytes of Computer Networking
## Project: Network Mapping & Ping Test Task

### 1. Network Mapping (Diagram)
The diagram below represents the topology of my local network, showing how my PC connects through the gateway to reach the internet.
### 2. Local Configuration Details
Using the `ipconfig` command on Windows, I identified the following network interface details:

* **IPv4 Address:** 172.20.6.46
* **Subnet Mask:** 255.255.254.0
* **Default Gateway:** 172.20.6.1
---

<img width="1024" height="904" alt="image" src="https://github.com/user-attachments/assets/57fd2a88-9949-4db0-8f84-a6b3aa3ec01d" />


<img width="587" height="453" alt="network map" src="https://github.com/user-attachments/assets/c061c908-cafa-4483-9560-5a5c9d4aa87a" />


### 📸 Connectivity Issue Identified
<img width="607" height="428" alt="network map2" src="https://github.com/user-attachments/assets/4058530c-3856-4a54-ab06-f01b0e487a54" />


### 📸 Troubleshooting Process
<img width="512" height="471" alt="network map3" src="https://github.com/user-attachments/assets/1bbd4556-c5a4-4b3c-9f14-c04b20084634" />
# Course 2: The Bits and Bytes of Computer Networking
## Project: Network Mapping & Ping Test Task
---

### 4. Conclusion
This project provided a practical look at the **Network Layer** of the TCP/IP model. By analyzing the `ipconfig` data and performing connectivity tests, I confirmed the following:

* **Network Identification:** My device is correctly configured within the `172.20.6.x` subnet, using `172.20.6.1` as the primary exit point (Gateway) for all external traffic.
* **Path Validation:** The successful ping to the **Default Gateway** confirms that the physical and data link layers (Wi-Fi) are functioning correctly.
* **Internet & DNS Health:** The successful pings to `8.8.8.8` and `www.google.com` prove that my network can route packets to the public internet and that **DNS (Domain Name System)** is correctly resolving human-readable names into IP addresses.

Overall, the local network is stable with low latency, and the configuration matches the expected star topology for a campus/office environment.
