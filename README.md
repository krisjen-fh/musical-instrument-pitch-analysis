# 🎶 Musical Instrument Pitch Analysis

This project focuses on detecting the **fundamental frequency (pitch)** of musical instrument sounds—specifically single-note acoustic guitar recordings—using **digital signal processing** techniques. Built in Google Colab, this notebook provides a step-by-step process to analyze sound signals and visualize pitch information.

---

## 📌 Project Overview

**Objective**:  
To identify the pitch (fundamental frequency) of acoustic guitar sounds using **Fast Fourier Transform (FFT)** and the **YIN algorithm** via `librosa`. This kind of analysis has potential applications in:
- Digital instrument tuning
- Automatic pitch recognition
- Music education tools
- Sound synthesis or instrument modeling

---

## 🎧 Dataset

The audio samples used in this project are sourced from **Freesound**:

🔗 [CS 80 Guitar Pack – Freesound.org](https://freesound.org/search/?q=single+note+guitar+&f=grouping_pack%3A%2229636_CS+80+GUITAR+1%22)

These are **single-note guitar samples**, ideal for analyzing the behavior of fundamental frequency and harmonic content.

---

## 🛠️ Technologies & Libraries Used

- Python (Google Colab)
- `librosa` – audio feature extraction
- `matplotlib` – waveform & pitch visualizations
- `numpy` – numerical computation
- `scipy` – signal processing
- `IPython.display` – interactive audio playback

---

## 🔍 Main Features

- 🎼 **Audio Signal Acquisition**: Loading and inspecting acoustic guitar audio signals.
- 📊 **Waveform & Spectrum Analysis**: Using FFT to visualize the frequency content.
- 🧠 **Pitch Detection**: Applying the YIN algorithm (`librosa.pyin`) to estimate the fundamental pitch over time.
- 🔎 **Comparative Analysis**: Distinguishing between normal vs. noisy signals and interpreting the harmonic structure.

---

## 📈 Key Takeaways

- **FFT** provides a detailed view of the frequency spectrum of musical notes.
- **YIN/pyin** is effective for monophonic pitch tracking in isolated instrument samples.
- Audio signals contain not just pitch, but also valuable information like **amplitude**, **harmonics**, and **timbre**.
- Well-structured digital audio processing can support **instrument classification**, **tuning assistance**, and **automated music analysis**.

---

## 👥 Team Members

This project was collaboratively developed by:
- Nazula Sinta Wati  
- Sofia Zahira Rohman  
- Krisjen Fraulein Hutagalung

---

## 📄 License

This project is open-source and available under the [Apache 2.0 License](LICENSE).

---

## 💡 Future Work

- Expand to multiple instruments (e.g., angklung, gamelan)
- Add clustering or classification based on pitch patterns
- Build a simple web interface for pitch analysis in real time
