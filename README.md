# NeuraFlow: Brain-Computer Interface (BCI) & 10-20 EEG Neural Signal Decoder

[![Live Workstation](https://img.shields.io/badge/Live-Workstation-0284c7?style=for-the-badge&logo=google-chrome)](https://tareq0001.github.io/NeuraFlow-BCI-Neural-Decoder/)
[![Architecture](https://img.shields.io/badge/Standard-10--20%20Montage-10b981?style=for-the-badge)](https://tareq0001.github.io/)
[![License](https://img.shields.io/badge/License-MIT-f59e0b?style=for-the-badge)](LICENSE)

An institutional-grade, browser-native Brain-Computer Interface (BCI) signal processing and cognitive state decoding workstation. Simulates a 16-channel clinical EEG acquisition stream conforming to the International 10-20 system at 250Hz with real-time Digital Signal Processing (DSP), Fast Fourier Transform (FFT) Power Spectral Density decomposition, and 3D Topographic Scalp Potential mapping.

---

## Key Features

1. **16-Channel 10-20 Standard Montage:**
   - Real physiological leads: `Fp1, Fp2, F3, F4, C3, C4, P3, P4, O1, O2, F7, F8, T3, T4, T5, T6`.
   - Multi-channel synchronized oscilloscope rendered at 60 FPS on high-DPI Canvas.
2. **Real-Time DSP Filter Pipeline:**
   - 0.5Hz - 50Hz Bandpass filter.
   - 50Hz / 60Hz Notch power-line rejection.
   - Ocular and muscle artifact mitigation.
3. **Power Spectral Density (PSD) Decomposition:**
   - **Delta ($\delta$, 0.5-4 Hz):** Deep sleep / fatigue states.
   - **Theta ($	heta$, 4-8 Hz):** Drowsiness and memory encoding.
   - **Alpha ($lpha$, 8-13 Hz):** Occipital resting rhythm and relaxed wakefulness.
   - **Beta ($eta$, 13-30 Hz):** Sensorimotor activation and active concentration.
   - **Gamma ($\gamma$, 30-50 Hz):** High-level cognitive cross-modal binding.
4. **3D Scalp Topographic Potential Map (Topomap):**
   - Real-time voltage potential field projection on anatomical head landmarks (Nasion, Inion, Preauricular points).
5. **Cognitive State & Motor Imagery Classification:**
   - Focus / Attention index calculator.
   - Mental workload and fatigue telemetry.
   - Sensorimotor rhythm ERD/ERS motor imagery decoding (Left vs Right hand movement intent).

---

## Live Demo
Experience the live workstation directly in your browser:
👉 **[https://tareq0001.github.io/NeuraFlow-BCI-Neural-Decoder/](https://tareq0001.github.io/NeuraFlow-BCI-Neural-Decoder/)**

---

## Author
**Tareq Aboushi (أ. طارق ابوعشي)**  
*AI Architect & Systems Engineer*  
Saudi Arabia 🇸🇦
