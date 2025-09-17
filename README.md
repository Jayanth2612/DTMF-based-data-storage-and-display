# DTMF Based Data Storage and Display

This project demonstrates a **DTMF (Dual-Tone Multi-Frequency) based data storage and display system**.  
It uses a **Proteus simulation** to decode tones, convert them into binary, store them using flip-flops, and finally display the results on a **7-segment display**.  
The project emphasizes **frequency filtering, encoding, modular design, and sequential data handling**.

---

## 🚀 Project Workflow
The project is divided into three stages (each with its own Proteus file):

1. **The Beginning – DTMF Decoder Module**
   - Implements a **4th-order filter** for precise frequency detection.  
   - Detects tones within **±40 Hz tolerance** of target frequencies.  
   - Produces **7 outputs** corresponding to the detected DTMF signals.

2. **The Middle – 7-to-4 Encoder Module**
   - Encodes the 7 detected outputs into a **compact 4-bit binary representation**.  
   - Simplifies processing for further storage and display.

3. **The End – Storage and Display Module**
   - Uses **multiplexers** as data selectors.  
   - Stores encoded data using **D flip-flops** for reliable key retention.  
   - Displays results on a **7-segment display**.

---
