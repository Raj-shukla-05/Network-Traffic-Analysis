# 🌐 Day 5 - Network Traffic Analysis Report

## 🧰 Tool Used
- Wireshark v4.6.4

## 🕵️ Summary
Captured live traffic on the local machine using Wireshark over the Wi-Fi interface. Common internet usage like browsing and pinging was used to generate network activity. Several standard protocols were identified.

## 📁 Capture Details
- Filename: `day5_network_capture.pcap`
- Interface: Wi-Fi
- Duration: 1 minute
- Activities performed:
  - Pinged `google.com`
  - Opened websites
  - Background applications (system/browser traffic)

---

## 📊 Protocols Identified

| Protocol | Description | Packet Count |
|----------|-------------|---------------|
| TCP      | Transmission Control Protocol for reliable data | ~600+ |
| ICMPv6   | Used for IPv6 ping responses | ~30+ |
| ARP      | Resolves IP to MAC on LAN | ~10+ |

> Replace counts with actual numbers from Wireshark if needed.

---

## 🔍 Observations

- **TCP**: Most traffic was TCP-based, likely from browser and background app communication.
- **ICMPv6**: Ping requests and replies from `google.com`.
- **ARP**: ARP packets were used by the system to resolve local IPs to MAC addresses.

---

## 📷 Screenshots

Screenshots showing filtered traffic for:
- TCP
- ICMPv6
- ARP

Saved under `/screenshots/` directory in this repository.

---

## ✅ Conclusion

This exercise demonstrated how to use Wireshark for basic packet capture and protocol inspection. It provided hands-on experience identifying different layers of network communication in real-time.
