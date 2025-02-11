
# **Network Sniffer in Python**  

## **📌 Overview**  
This project is a **Python-based network sniffer** that captures and analyzes network traffic on your system.  
It monitors **active network connections** and displays **real-time packet information** such as:  
- **Source & Destination IPs**  
- **Protocol Type (TCP/UDP)**  
- **Active network connections** on the system  

---

## **📜 How It Works**  
The script runs an **infinite loop**, performing two main tasks:  
1️⃣ **Captures network packets** using `scapy.sniff()` and extracts important details.  
2️⃣ **Monitors active connections** using `psutil.net_connections()` to see ongoing communications.  

### **🔹 Features**  
✅ Captures incoming and outgoing **TCP/UDP packets**  
✅ Extracts **source & destination IPs, protocol type, and TTL**  
✅ Monitors **live network connections (ESTABLISHED connections)**  
✅ Runs continuously and **updates every 5 seconds**  
✅ **Gracefully exits** when stopped (`Ctrl + C`)  

---

## **⚙️ Installation & Setup**  
Follow these steps to clone and run the network sniffer:  

### **1️⃣ Clone the Repository**
git clone https://github.com/Dominion002/Network-Sniffer.git
cd network-sniffer

Install dependencies
pip install scapy psutil

Instal Npcap For windows users
https://npcap.com

🚀 Running the Network Sniffer
Run the script with Administrator Privileges for proper packet sniffing:
cd path\to\network-sniffer
python packet_sniffer.py

