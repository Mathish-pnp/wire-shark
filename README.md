# 🌐 Task 5: Capture and Analyze Network Traffic Using Wireshark

## 🎯 Objective

Use Wireshark to capture live network packets and identify at least three basic network protocols. The goal is to develop hands-on packet analysis skills and improve awareness of how network protocols operate in real time.

---

## 🛠 Tools Required

- **Wireshark** – Free network protocol analyzer  
  Download: https://www.wireshark.org/download.html

- **Web browser** – To generate HTTP/DNS traffic
- **Terminal/Command Prompt** – To generate ping (ICMP) or manual DNS/TCP queries

---


---

## Instructions

### ✅ 1. Install Wireshark
- Download and install from: [https://www.wireshark.org](https://www.wireshark.org)
- Allow it to install **WinPcap/Npcap** when prompted (for packet capturing support)

---

### ✅ 2. Start Capturing Packets
1. Launch Wireshark.
2. Select the **active network interface** (usually "Wi-Fi" or "Ethernet").
3. Click the **blue shark fin icon** to start capturing live packets.

📷 *Tip:* Optionally take a screenshot showing the capture starting.

---


Capture live network packets using **Wireshark** and analyze basic traffic protocols (HTTP, DNS, TCP, etc.).

---

## 📦 Folder Contents

| File/Folder                      | Description                                |
|----------------------------------|--------------------------------------------|
| `captures/network-traffic-sample.pcap` | The actual captured network traffic file  |
| `screenshots/`                   | Screenshots of protocol filtering (optional) |
| `README.md`                      | This report/documentation                  |

---

### ✅ 3. Generate Network Traffic
While capturing:

- Open a web browser and visit:  


- Open **Command Prompt** and run:  
```bash
ping 192.168.26.144


