# 🦠 FHNN: Frequency Harmonic Neural Network for Monkeypox Detection

> 🛠️ Python | Deep Learning | Fourier Neural Operator  
> 📦 Lightweight: Only 0.629M parameters

## 🧠 Overview

In response to the 2022–2023 global Monkeypox outbreak, this project introduces **FHNN** — a lightweight deep learning model for early detection of Monkeypox through medical imaging. FHNN is designed for **resource-constrained environments**, making it ideal for deployment in regions with limited access to skilled healthcare professionals.

## 🔬 Core Contributions

- 🧩 Introduces four novel modules:
  - Harmonic Channel Attention Block (HCAB)
  - Harmonic Spatial Attention Block (HSAB)
  - Harmonic Attention Channel Shuffle (HACS)
  - Time-Frequency Feature Learning Block (TFFLB)
- 🔁 Leverages **Fourier Neural Operator (FNO)** to learn time and frequency domain features
- ⚙️ Ultra-efficient: Only **0.629M parameters**

## 📊 Results

| Dataset                | Accuracy (%) | F1 Score (%) |
|------------------------|--------------|--------------|
| MSLDv2                 | 98.65        | 98.71        |
| MSID                   | 100.00       | 100.00       |
| Monkeypox-2022 Dataset | 99.58        | 99.62        |

## ✅ Highlights

- 🧠 Accurate & Robust on Skin Lesion Image Datasets  
- 💡 Frequency-aware attention with minimal computational overhead  
- 💻 Suitable for real-time **computer-aided diagnosis (CAD)** in low-resource settings  
