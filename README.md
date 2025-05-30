# RLC_BandStop_Filter_LTspice
Simulated RLC Band-Stop (Notch) Filter in LTspice. Sharp notch at ~503 kHz, validated with -3 dB bandwidth.
This project demonstrates a Band-Stop (Notch) Filter using an RLC network simulated on LTspice. It suppresses a narrow frequency band centered around ~503 kHz — ideal for noise filtering applications.
---
## 🔧 Circuit Configuration
- R1 = 1 kΩ  
- L1 = 100 μH  
- C1 = 1 nF  
- AC Source = 1V (AC Analysis)  
- Simulation Command: .ac dec 100 10 10Meg
---
## 📊 Observations
- *Theoretical Notch Frequency:*  
  \[
  f = \frac{1}{2\pi\sqrt{LC}} ≈ 503 kHz
  

- *Simulated Notch Frequency:* ~500 kHz  
- *-3 dB Cutoff Points:*  
  - Left: ~433.17 kHz  
  - Right: ~578.26 kHz  
- *Bandwidth:* ~145.09 kHz  
- *Deep Attenuation* clearly visible in the output curve
---
## 📂 Files Included

- .asc file (LTspice schematic)  
- Circuit Diagram Screenshot  
- Simulation Graph with cursor placement

---

## ⚙️ Tools Used

- LTspice  
- Frequency formula: f = 1 / (2π√LC)  
- Manual cursor-based bandwidth validation

---

## 🚀 By Vishal Singh

EV & VLSI transition in progress. Hands-on with LTspice + KiCad + ISO 26262.  
Certified Lean Six Sigma Green Belt with 10+ years compliance experience.

📌 GitHub: [https://github.com/VishalSingh-ML](https://github.com/VishalSingh-ML)  
📌 LinkedIn: [https://linkedin.com/in/your-profile](https://linkedin.com/in/your-profile)
