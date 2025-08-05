# 🛡️ Built-In PC Firewall Configuration – Cisco Packet Tracer

This project demonstrates how to configure and test the **built-in firewall on a PC** in Cisco Packet Tracer. The built-in firewall allows you to control incoming and outgoing traffic directly on the PC by allowing or blocking specific services (ports).

---

## 📁 Project Overview

The goal of this project is to simulate **host-level firewall security** where a PC uses its own firewall to control access to services such as:

- 🌐 HTTP (Web browsing)
- 📁 FTP (File transfer)
- 🛰️ ICMP (Ping)

This helps learners understand how **client-side firewalls** protect individual systems even within a larger secure network.

---

## 🧱 Network Components

- 💻 PC (with built-in firewall enabled)
- 💻 Other client PCs (used for testing)
- 🌐 Server (provides HTTP, FTP, etc.)
- 🔀 Switch (for LAN connectivity)

---

## 🔐 Firewall Configuration Details

### ✅ Where it's configured:
- Go to the PC → **Config Tab** → **Firewall**

### ✅ How it works:
- You can **allow** or **deny** access to different ports and protocols.
- For example:
  - **Allow HTTP** (Port 80)
  - **Deny FTP** (Port 21)
  - **Deny ICMP** (Ping)

### ✅ Example Setup:
| Service | Port | Status     |
|---------|------|------------|
| HTTP    | 80   | ✅ Allowed  |
| FTP     | 21   | ❌ Denied   |
| ICMP    | —    | ❌ Denied   |

---

## 🧪 Testing Steps

1. Open the `.pkt` file in Cisco Packet Tracer.
2. Use another PC to:
   - Ping the PC with the firewall → Should **fail** if ICMP is blocked.
   - Access `http://<PC-IP>` in a browser → Should **work** if HTTP is allowed.
   - Use FTP → Should **fail** if FTP is blocked.
3. Adjust the firewall settings and retest to observe changes in behavior.

---

## 🎯 Learning Outcomes

- Understand how **built-in PC firewalls** work in a network.
- Learn to enable or disable specific ports/services.
- Gain practical experience in **host-level traffic control**.
- Observe how traffic is filtered at the device level, not just at routers.

---

## 📌 Author

**Harshit **  
📧 06harshit7230@gmail.com  
🌐 [GitHub: Harshitsss](https://github.com/Harshitsss)

---

💡 *This project is useful for understanding client-side security and testing service-level access control in simulated networks.*
