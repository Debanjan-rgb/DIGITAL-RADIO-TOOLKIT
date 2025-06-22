# DIGITAL-RADIO-TOOLKIT
A  Python-based Software-Defined Radio (SDR) signal analyzer designed for simulating, visualizing, and analyzing radio signals without requiring physical hardware. It enables users to inspect .wav audio signals, compute Fast Fourier Transforms (FFT), generate spectrograms, and detect dominant frequencies—all in a clean and extensible codebase.

---

##  Features

-  **WAV Signal Input** – Simulate RF signals using `.wav` audio files.
-  **FFT Spectrum Visualization** – View frequency spectrum in real-time.
-  **Spectrogram Plotting** – Understand signal variation over time.
-  **Peak Frequency Detection** – Identify dominant frequency components.
-  **Modular Design** – Built for future enhancements like modulation/demodulation or SDR hardware integration.

---

## Preview

![image](https://github.com/user-attachments/assets/28855a8f-b3eb-466e-b502-a1e5aa966f83)


> *Example spectrum and spectrogram visualizations from a sample `.wav` signal.*

---

## Tech Stack

| Tool / Library | Use |
|----------------|-----|
| Python         | Core programming language |
| NumPy          | Signal processing and numerical operations |
| SciPy          | Signal loading and transformations |
| Matplotlib     | Plotting spectrograms and frequency spectrums |
| Wave / PyDub   | Audio file handling |

---

## Installation

```bash
git clone https://github.com/yourusername/WaveScope.git
cd WaveScope
pip install -r requirements.txt
