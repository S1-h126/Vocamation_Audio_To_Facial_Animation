# Vocamation_Audio_To_Facial_Animation
## Introduction

**Vocamation** is a deep learning project that converts audio speech input into phoneme sequences and corresponding facial animations (visemes).  
It uses **MFCC features** extracted from audio and a **Bidirectional LSTM model** to predict phonemes, enabling lip-syncing for animation.

---

## Features
- Audio-to-phoneme conversion using deep learning
- Phoneme-to-viseme mapping for facial animation
- Real-time recording and processing

 ## Creating virtual enviroment
  python -m venv venv
  source venv/bin/activate    # Linux/macOS

  
  venv\Scripts\activate       # Windows

##Installing requirements
  pip install -r requirements.txt

## For backend
python api.py

##For frontend
npm start
