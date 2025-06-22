# DIGITAL-RADIO-TOOLKIT
A  Python-based Software-Defined Radio (SDR) signal analyzer designed for simulating, visualizing, and analyzing radio signals without requiring physical hardware. It enables users to inspect .wav audio signals, compute Fast Fourier Transforms (FFT), generate spectrograms, and detect dominant frequencies—all in a clean and extensible codebase.



With support for `.wav` input files, real-time spectrum analysis, peak detection, and modular signal processing, **WaveScope** is the perfect project for your portfolio or academic exploration into telecommunications and digital signal processing (DSP).

---

## 🎯 Features

- 🎧 **WAV Signal Input** – Simulate RF signals using `.wav` audio files.
- 📊 **FFT Spectrum Visualization** – View frequency spectrum in real-time.
- 🌈 **Spectrogram Plotting** – Understand signal variation over time.
- 🔍 **Peak Frequency Detection** – Identify dominant frequency components.
- 🧩 **Modular Design** – Built for future enhancements like modulation/demodulation or SDR hardware integration.

---

## 🖼️ Preview

<img src="assets/spectrum_example.png" alt="Spectrum Example" width="600"/>
<img src="assets/spectrogram_example.png" alt="Spectrogram Example" width="600"/>

> *Example spectrum and spectrogram visualizations from a sample `.wav` signal.*

---

## 🛠 Tech Stack

| Tool / Library | Use |
|----------------|-----|
| Python         | Core programming language |
| NumPy          | Signal processing and numerical operations |
| SciPy          | Signal loading and transformations |
| Matplotlib     | Plotting spectrograms and frequency spectrums |
| Wave / PyDub   | Audio file handling |

---

## 🧪 Installation

```bash
git clone https://github.com/yourusername/WaveScope.git
cd WaveScope
pip install -r requirements.txt
