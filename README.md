# Shazam-Style Music Recognition App (MDST Project)

This project contains both the **frontend** (React Native + Expo) and **backend** (Python + Flask + audio fingerprinting) for a Shazam-style music recognition system.

## Project Structure

project/
│
├── frontend/ # React Native app with Recorder interface
└── backend/ # Python backend with fingerprinting + prediction


## Frontend (Expo)
- Built with React Native + Expo
- Uses audio recording
- Sends audio samples to the backend for fingerprint matching

## Backend (Flask)
- Computes song fingerprints using constellation maps + hashing
- Matches uploaded audio samples to a database of known tracks
- Uses librosa for feature extraction

---

# Getting Started

## 1. Backend
python3 predict_song.py


## 2. Frontend
npx expo start --tunnel


