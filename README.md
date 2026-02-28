# Quantitative Kinematics & Regime Decoding

![Impulse-X Terminal Preview](assets/preview.png)

## The Problem: The Phase Lag Death Spiral
Most systematic strategies fail because they rely on **time-averaging indicators** (Moving Averages, RSI, MACD). In a non-stationary system like the limit order book, averaging past data creates a terminal phase lag. By the time your indicator signals a "trend," the institutional move is already exhausted.

## The Solution: Market Physics
This repository demonstrates a **Kinematic approach** to price action. Instead of treating price as a series of static candles, we treat it as a continuous physical object in motion.

### Core Mathematical Pillars:
* **Savitzky-Golay Filtering:** Replacing lagging MAs with polynomial-fit derivatives to extract instantaneous **Velocity ($v$)** and **Acceleration ($a$)**.
* **Causal Hilbert Transforms:** Utilizing reflective padding to extract the instantaneous phase of the market cycle without "end-point repainting."
* **Shannon Entropy ($H$):** Measuring the Information Density of the signal to identify High Chaos environments where trend-following is statistically suicidal.
* **Hidden Markov Models (HMM):** A Bayesian framework that synthesizes Kinematics and Entropy to decode the hidden structural regime of the market (e.g., *Bull Drift* vs. *Kinematic Dip*).

---

## 🔬 High-Performance Research
The logic in this repo is a subset of the **Impulse-X Engine**, a high-speed terminal environment optimized for disciplined traders who require objective math over gut feelings.

### Performance Characteristics:
* **Strictly Causal:** No look-ahead bias. No repainting.
* **Signal Demodulation:** Separating structural alpha from high-entropy noise.
* **Regime Awareness:** Automatically adjusting bias based on the HMM transition matrix.

---

## 📘 Deep Dive Documentation
For the full mathematical derivation, LaTeX frameworks, and terminal implementation specs, visit the official hub:

👉 **[Impulse-X Documentation & Technical Manual](https://konvsys.github.io/impulse-docs/)**

---
[Secure your Alpha Seat on Gumroad](https://konvolut.gumroad.com/l/wjtou)
