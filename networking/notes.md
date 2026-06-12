# 🌐 Networking Notes

## What is Networking?
- Network = two or more devices connected sharing information
- The internet is the biggest network in the world

### Device Identifiers
| Identifier | Description |
|---|---|
| **IP Address** | Device address on the network (e.g. 192.168.1.1) — can change |
| **MAC Address** | Physical identifier on the network card (e.g. a4:c3:f0:85:ac:2d) — never changes |

---

## Intro to LAN
- **LAN** = Local Area Network (home, office, school)

### Main Equipment
| Equipment | Function |
|---|---|
| **Switch** | Connects devices inside the same local network |
| **Router** | Connects different networks and links LAN to internet |
| **Access Point** | Enables wireless connection (Wi-Fi) |

### Network Topologies
| Topology | How it works | Status |
|---|---|---|
| **Star** ⭐ | All devices connect to a central point (switch) | Most used today |
| **Bus** 🔴 | All devices share one central cable | Old — if cable breaks, everything stops |
| **Ring** 🟡 | Each device connects to the next in a circle | Old — unstable |

---

## 🔧 First Command Learned
```bash
dirb http://target.com
```
- Scans for hidden directories on websites
- Tests hundreds of names automatically
- **Only use in authorized environments or labs**

### Vulnerability Found: Broken Access Control
- When restricted pages are accessible without login
- One of the most common vulnerabilities in the real world

---

> ⚠️ **Golden Rule:** Never use security tools on real targets without written permission.
> This is a crime in Brazil and worldwide.
