# Lab 4 — Follow TCP Stream

**Score:** 100/100  
**Date Completed:** 29 October 2026  
**Reference:** [networkwalks.com/wireshark-lab4/](https://networkwalks.com/wireshark-lab4/)

## 🎯 Objective
Reconstruct a full TCP conversation using Wireshark's "Follow TCP Stream" feature and extract sensitive details from the chat.

## 🧠 Skills Practiced
- Right-click → Follow → TCP Stream
- Reading reconstructed chat conversations
- Identifying chat ports and participants
- Extracting passwords and hidden text properties

## 📝 Tasks Completed
1. ✅ Capture the traffic
2. ✅ Find the chat port
3. ✅ Who started the chat?
4. ✅ Stream number
5. ✅ Size of the chat
6. ✅ Who needs help?
7. ✅ The problem drive
8. ✅ Temporary password
9. ✅ Guest Wi-Fi password
10. ✅ Text colour

## 📸 Screenshot

![Lab 4 Screenshot](../../screenshots/lab4-follow-tcp-stream.png)

## 🔍 Key Findings
Following the TCP stream revealed a full chat session containing a **temporary password** and a **guest Wi-Fi password** shared in plain text, along with a hidden text-color detail embedded in the conversation.
