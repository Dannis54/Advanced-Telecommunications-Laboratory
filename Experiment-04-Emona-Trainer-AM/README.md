# 🧪 Experiment 4: Amplitude Modulation (AM) Using Emona Telecoms-Trainer 101

---

## 📌 Objective
- Generate amplitude-modulated (AM) signals using Emona Telecoms-Trainer 101.  
- Measure carrier amplitude, message amplitude, and modulation index.  
- Observe AM waveform variations on an oscilloscope.  
- Connect theoretical formulas with experimental results.

---

## 📖 Introduction
**Amplitude Modulation (AM)** is a technique where the **amplitude of a high-frequency carrier signal** is varied in proportion to a **message signal**. AM is widely used in analog radio broadcasting.  

Using the **Emona Telecoms-Trainer 101**, we can generate both the carrier and message signals and observe the resulting AM waveform with a **dual-channel oscilloscope**.  

**Theoretical Background & Formulas:**

1. **AM Signal Equation**:v_AM(t) = [V_c + V_m × sin(2π f_m t)] × sin(2π f_c t)
   - V_c = carrier amplitude  
- V_m = message amplitude  
- f_c = carrier frequency  
- f_m = message frequency  

2. **Modulation Index (Depth of Modulation)**:m = (V_max - V_min) / (V_max + V_min)
   - V_max = maximum envelope voltage of AM waveform  
- V_min = minimum envelope voltage of AM waveform  
- 0 < m ≤ 1 (for standard AM without overmodulation)

3. **Carrier and Message Relation**: V_AM_max = V_c × (1 + m)
V_AM_min = V_c × (1 - m)

4. **Frequency Verification Using Oscilloscope**:- T = period of the carrier waveform  
- Used to verify carrier frequency and modulation integrity

---

## 🧰 Materials
- Emona Telecoms-Trainer 101  
- Dual-channel oscilloscope (≥20 MHz recommended)  
- Patch leads / banana cords  
- Function generator (if needed for message signal)  
- Calculator  
- Notebook  

---

## 🔬 Procedure
### Part 1 — Setup
1. Power on Emona Trainer and oscilloscope.  
2. Connect **carrier output** to oscilloscope CH1.  
3. Connect **message output** (audio or low-frequency sine) to modulating input.  
4. Ensure oscilloscope ground leads are connected properly.

### Part 2 — Observing AM Waveform
1. Set oscilloscope **timebase** to display multiple cycles of carrier.  
2. Adjust **vertical scale** to fit waveform.  
3. Observe the carrier **envelope shaped by message signal**.

### Part 3 — Measuring Amplitudes
1. Measure **V_max** and **V_min** on oscilloscope using grid lines and V/div settings.  
2. Measure **carrier amplitude V_c** directly from unmodulated carrier.  
3. Measure **message amplitude V_m** (difference between V_max and V_min as per formulas).

### Part 4 — Calculating Modulation Index
1. Use formula:m = (V_max - V_min) / (V_max + V_min)
   
2. Verify **AM waveform envelope** matches expected modulation depth.  

### Part 5 — Variation of Message Signal
1. Increase message amplitude; observe increase in envelope swing.  
2. Decrease message amplitude; observe decrease in envelope swing.  
3. Record observations for different modulation depths.

---

## 📊 Observations
- AM waveform envelope clearly visible on oscilloscope.  
- Modulation depth changed proportionally with message amplitude.  
- Carrier frequency remained constant while amplitude varied.  
- Calculated **modulation index (m)** matched visually observed envelope.

---

## 🧠 Discussion
- AM signals illustrate **information encoding via amplitude variation**.  
- The **carrier signal** remains at constant frequency, while the **message modulates amplitude**.  
- Accurate measurements require proper **V/div and s/div settings** on the oscilloscope.  
- Overmodulation (m > 1) leads to distortion; observing V_max and V_min prevents this.  
- This experiment demonstrates **link between theoretical AM equations and practical observation** on Emona Trainer.

---

## ✅ Conclusion
- AM waveform successfully generated and analyzed using Emona Trainer.  
- Modulation index calculations verified with measured V_max and V_min.  
- Practical waveform matched theoretical predictions, confirming AM principles.

---

## ✍️ Reflection
Hands-on AM observation strengthened understanding of **analog modulation principles**. Using the oscilloscope to measure amplitudes and calculate modulation index connected **theory to real signals**, essential for analog communications.










