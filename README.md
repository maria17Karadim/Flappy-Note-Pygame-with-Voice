# 🎵 Flappy Note

**Flappy Note** is a voice-controlled adaptation of the classic Flappy Bird game, developed using **Pygame**, **PyAudio**, and **Aubio** libraries. This project, created by Maria Karademetropoulou in 2024, transforms microphone input into pitch and volume data to control the bird's movements, enabling hands-free gameplay. 🐦🎤

---

## ✨ Key Features
- 🎶 Real-time audio analysis for pitch detection (using Aubio) and volume thresholding to navigate pipes.
- 🎮 Intuitive UI with menu, play, replay, and game over screens, plus adjustable mic sensitivity and balance settings.
- 🖼️ 600x600 pixel gameplay window featuring dynamic scoring, sound-reactive bird control, and smooth animations.

---

## 🛠️ Technologies
- **Pygame:** Handles graphics, events, and game loop.
- **PyAudio:** Captures live audio streams in float32 format at configurable rates (e.g., 44100 Hz).
- **Aubio:** Computes pitch (e.g., around 100 Hz examples) and processes audio buffers.

---

## 🎮 How to Play
Capture your voice: higher pitch/volume makes the bird ascend, while pipes move automatically—avoid collisions for high scores! 🐦💨  
Run the main Python script after installing dependencies via:

```bash
pip install pygame pyaudio aubio
