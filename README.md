# 🎵 Song Genre Classification using Audio Data

![Python](https://img.shields.io/badge/Python-3.8-blue.svg)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Enabled-brightgreen)
![License](https://img.shields.io/badge/License-MIT-lightgrey)

> A machine learning-based project that classifies songs into their respective genres using audio data and feature extraction techniques like MFCC.

## 🔍 Overview

This project focuses on building a genre classification model using machine learning and audio processing techniques. The audio data is processed to extract features such as **MFCCs (Mel-frequency cepstral coefficients)**, which are then used to train various classifiers.

## 🛠 Tech Stack

- **Language**: Python
- **Libraries**: Librosa, NumPy, Pandas, Scikit-learn, Matplotlib
- **Audio Features**: MFCC, Chroma, Spectral Contrast
- **Models**: Random Forest, KNN, SVM

## ⚙️ Installation

```bash
git clone https://github.com/rsrujan/Song-Genre-Classification-using-Audio-data.git
cd Song-Genre-Classification-using-Audio-data
pip install -r requirements.txt
```

## 📈 Usage

```bash
python extract_features.py
python train_model.py
python predict_genre.py test_audio.wav
```
