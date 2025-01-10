# Network Traffic Analysis with Wireshark

This project demonstrates the process of capturing and analyzing network traffic using Wireshark, a popular network protocol analyzer. The main goal is to develop the foundational skills required for effective network traffic analysis, which is an essential competency for cybersecurity professionals.

---

## Project Objectives:
- Install and set up Wireshark.
- Capture network traffic from a specified network interface.
- Perform basic analysis of captured packets, including filtering traffic based on specific protocols, IP addresses, and ports.
- Inspect packet components for deeper insights.

---

## Prerequisites:
- Basic knowledge of computer networking.
- A system with internet connectivity.
- Root or sudo access for installation and traffic capture.

---

## Installation Steps:
1. **Download Wireshark**
   - Visit [Wireshark's official website](https://www.wireshark.org/download.html) and download the installer suitable for your operating system (Windows, macOS, or Linux).

2. **Install Wireshark**
   - Follow the installation instructions for your OS.
     - **Windows/macOS**: Use the provided installer and follow the on-screen prompts.
     - **Linux**: Install using the terminal:
       ```bash
       sudo apt update
       sudo apt install wireshark
       sudo usermod -aG wireshark $USER
       newgrp wireshark
       ```

---

## Analysis Process:

### 1. **Checking HTTP Traffic:**
Filtered HTTP traffic using Wireshark's filter options to identify requests and responses. This highlights web activity on the network.

![Checking HTTP Traffic](https://github.com/user-attachments/assets/73623432-1eee-4ae0-9b41-40daf901e31b)

### 2. **Analyzing TCP Traffic:**
Captured and filtered TCP packets to observe network communications at the transport layer.

![Checking TCP Traffic](https://github.com/user-attachments/assets/d4553f61-b036-4434-9869-f6f61d62a3f1)

### 3. **Filtering Traffic by Specific IP Address:**
Filtered packets originating from or destined to a specific IP address, providing insights into communication patterns.

![Filtering by IP Address](https://github.com/user-attachments/assets/a48015bf-a902-4caa-a7d1-fc94253b80a3)

### 4. **Filtering Traffic by Specific Port:**
Analyzed network activity on a specific port to investigate protocols or services running on the system.

![Filtering by Port](https://github.com/user-attachments/assets/0dbfa342-969e-49f4-8c8f-c2f3727a54c5)

### 5. **Inspecting Packet Components:**
Explored packet details, including headers and payloads, to understand the structure of captured network packets.

![Inspecting Packet Components](https://github.com/user-attachments/assets/4a2dd887-8f30-4747-8eb3-981ca6f94acf)

---

## Key Features:
- Captured real-time traffic for analysis.
- Filtered data based on:
  - Protocols (e.g., HTTP, TCP).
  - IP addresses.
  - Ports.
- Inspected packet contents for detailed insights.
- Documented key findings and analysis.

---

## Conclusion:
This project successfully demonstrates the use of Wireshark for network traffic analysis. It showcases practical techniques for capturing, filtering, and inspecting packets, helping build essential cybersecurity skills. Further exploration of Wireshark's advanced features is recommended to deepen understanding and proficiency.

---



















# Network-Traffic-Analysis-with-Wireshark

The main goal of this project is to capture network traffic and  perform basic analysis
....


![image](https://github.com/user-attachments/assets/4a2dd887-8f30-4747-8eb3-981ca6f94acf)

**Checking Http:**
![image](https://github.com/user-attachments/assets/73623432-1eee-4ae0-9b41-40daf901e31b)

**Checking tcp:**

![image](https://github.com/user-attachments/assets/d4553f61-b036-4434-9869-f6f61d62a3f1)

**Checking Specific ip address:**

![image](https://github.com/user-attachments/assets/a48015bf-a902-4caa-a7d1-fc94253b80a3)

**Checking with specific port:**

![image](https://github.com/user-attachments/assets/0dbfa342-969e-49f4-8c8f-c2f3727a54c5)

**Inspecting packet components:**

![image](https://github.com/user-attachments/assets/818a8710-56b7-4e25-bcc3-c455e4e1a87e)


