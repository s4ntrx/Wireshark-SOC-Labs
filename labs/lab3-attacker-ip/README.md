# Lab 3 — Identify the Attacker's IP

**Score:** 99/100  
**Date Completed:** 29 October 2026  
**Reference:** [networkwalks.com/wireshark-lab3/](https://networkwalks.com/wireshark-lab3/)

## 🎯 Objective
Identify the attacker's IP address by analyzing captured traffic and isolating malicious scanning activity.

## 🧠 Skills Practiced
- Filtering SYN packets with `tcp.flags.syn == 1`
- Distinguishing attacker traffic from legitimate traffic
- Identifying the target host and probed ports
- Classifying the attack type (port scan)

## 📝 Tasks Completed
1. ✅ Capture the traffic
2. ✅ Show only SYN packets
3. ✅ Find the attacker (1 hint used)
4. ✅ Find the target
5. ✅ Source port
6. ✅ Ports probed
7. ✅ Open ports
8. ✅ Reply for closed ports
9. ✅ Closed ports
10. ✅ Attack type

## 📸 Screenshot

![Lab 3 Screenshot](../../screenshots/lab3-attacker-ip.png)

## 🔍 Key Findings
The attacker was identified by filtering SYN packets and observing a high volume of connection attempts from a single source IP toward a target host across multiple destination ports — a classic **TCP SYN port scan** pattern.
