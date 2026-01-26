# 🧪 Experiment 3: Signal Modeling Using Emona Telecoms-Trainer 101

---

## 📌 Objective
- Analyze and model signals using Emona Telecoms-Trainer 101 modules.  
- Compare theoretical calculations with observed waveforms.  
- Study amplitude, phase, and frequency relationships in analog signals.

---

## 📖 Introduction
The **Emona Telecoms-Trainer 101** is a modular platform for analog communication experiments. It allows students to observe **signal generation, summation, phase shifting, buffering, and voltage-controlled frequency output (VCO)**.

This experiment focuses on **signal modeling using equations**. By combining theory and practice, we can predict outputs mathematically and verify them experimentally.

**Key Theoretical Concepts & Formulas:**

1. **Sine Wave (Master Signals Module)**  v(t) = V_m × sin(2π f t + φ)
   - V_m = amplitude  
- f = frequency  
- φ = initial phase  

2. **Adder Module (Signal Summation)**  v_out(t) = A × v_A(t) + B × v_B(t)
   - A, B = gain factors for inputs  
- v_A, v_B = input signals  

3. **Phase Shifter Module**  v_out(t) = V_m × sin(2π f t + φ + θ
   - θ = phase shift applied  
- Shows output can **lead or lag** the input signal  

4. **Voltage-Controlled Oscillator (VCO)**  f_out = f_center + K_v × V_control
- f_center = center frequency  
- K_v = VCO sensitivity  
- V_control = applied control voltage  

5. **Frequency Measurement from Period:**  f = 1 / T
   - T = period of waveform  

6. **Phase Difference Measurement:**  φ = (difference in divisions / period in divisions) × 360°- Used when comparing sine and cosine outputs  

These formulas allow us to **predict amplitude, phase, and frequency outputs** for the Emona modules before measurement.

---

## 🧰 Materials
- Emona Telecoms-Trainer 101  
- Dual-channel oscilloscope (≥20 MHz recommended)  
- Patch leads / banana cords  
- Calculator  
- Notebook  

---

## 🔬 Procedure
### Part 1 — Master Signals
1. Connect **2 kHz sine output** to CH1 of oscilloscope.  
2. Observe waveform; measure **Vpp**, **T**, and calculate **f**:  

3. Repeat for **100 kHz sine** and **100 kHz cosine** outputs.  

### Part 2 — Adder Module
1. Connect signals to **inputs A and B** of Adder module.  
2. Adjust gains **A** and **B** to desired levels.  
3. Observe output on CH2; calculate expected waveform:  
4. Compare predicted amplitude with measured Vpp.

### Part 3 — Phase Shifter Module
1. Apply 2 kHz sine input to Phase Shifter.  
2. Observe **input (CH1)** and **output (CH2)** in DUAL mode.  
3. Vary Phase Adjust; record **lead or lag** behavior:  
4. Test **0° and 180° Phase Change** positions; note max shift achievable.

### Part 4 — VCO Module
1. Set VCO Gain and Frequency Adjust to mid-position.  
2. Connect VCO output to CH1; measure **Vpp** and **f_out**.  
3. Apply **Variable DC Voltage (V_control)**; observe frequency changes:  
4. Record min/max frequencies for **LO** and **HI** range settings.  

---

## 📊 Observations
- Master Signals produced stable sine and cosine waveforms.  
- Adder output matched predicted **weighted sum**.  
- Phase Shifter output could **lead or lag** input; range approached 360°.  
- VCO output frequency increased linearly with control voltage.  
- Observed frequencies closely matched calculations using formulas.

---

## 🧠 Discussion
- **Adder Module:** Demonstrates **linear superposition**. Varying gains A and B changes output amplitude predictably.  
- **Phase Shifter:** Horizontal displacement of waveform confirms **phase manipulation**. Practical limitations due to module design.  
- **VCO Module:** Demonstrates **frequency modulation with voltage**; essential for FM transmitters and PLL circuits.  
- **Equation Verification:** Experimental measurements matched theoretical predictions, validating the **signal modeling approach**.

---

## ✅ Conclusion
- Emona Telecoms-Trainer 101 modules accurately follow their theoretical formulas.  
- Signal modeling using equations is validated experimentally.  
- Students can predict and measure **amplitude, phase, and frequency** effectively.

---

## ✍️ Reflection
This experiment strengthened understanding of **theoretical modeling vs. real-world signals**. By combining Master Signals, Adder, Phase Shifter, and VCO modules, I learned how analog signals behave mathematically and practically, which is foundational for **communications engineering**.










