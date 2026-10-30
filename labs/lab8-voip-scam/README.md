# Lab 8 — Catch the Call Scammer

**Score:** 100/100  
**Date Completed:** 29 October 2026  
**Reference:** [networkwalks.com/wireshark-lab8/](https://networkwalks.com/wireshark-lab8/)

## 🎯 Objective
Investigate a VoIP capture, replay the call, and identify the scammer's details and stolen card information.

## 🧠 Skills Practiced
- Identifying SIP call setup traffic
- Identifying RTP voice streams
- Using Wireshark's **RTP Player** to replay audio
- Extracting caller extension, name, and codec
- Capturing card number and expiry from the call

## 📸 RTP Player — Call Replay

![RTP Player Screenshot](../../screenshots/lab8-voip-scam.png)

## 📝 Tasks Completed
1. ✅ Capture the traffic
2. ✅ Call setup protocol
3. ✅ Voice protocol
4. ✅ Caller extension
5. ✅ Caller name
6. ✅ The codec
7. ✅ Who answered
8. ✅ Card number
9. ✅ Expiry date
10. ✅ The fix

## 🔍 Key Findings
- **Call setup:** SIP
- **Voice:** RTP (G.711 PCMU)
- The RTP Player was used to replay the audio and identify the scammer's **caller name**, **extension**, and the **card number** and **expiry date** disclosed during the call.
- **Fix:** Enforce encrypted VoIP (SRTP/TLS) and caller verification.
