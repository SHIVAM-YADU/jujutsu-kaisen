# Jujutsu Kaisen – Gesture Controlled Cursed Techniques

An interactive web experiment that allows users to trigger **anime-inspired cursed techniques using hand gestures** in real time.

Inspired by the anime [Jujutsu Kaisen](chatgpt://generic-entity?number=0), this project explores how **computer vision and 3D web graphics** can create immersive and interactive web experiences.

---

## Demo

Using your webcam, the system detects **hand gestures** and activates different cursed techniques with dynamic visual effects.

Techniques included:

- 🔵 Domain Expansion – Infinite Void
- 🔥 Domain Expansion – Malevolent Shrine
- 🟣 Secret Technique – Hollow Purple
- 🔴 Reverse Cursed Technique – Red

Each gesture triggers a unique **3D particle-based animation** rendered in real time.

---

## Tech Stack

- **JavaScript**
- **Three.js** – 3D particle rendering
- **MediaPipe Hands** – Real-time hand tracking
- **WebGL** – GPU accelerated graphics
- **HTML5 / CSS3**

---

## How It Works

1. The browser accesses the **webcam**.
2. **MediaPipe Hands** detects hand landmarks in real time.
3. The system recognizes specific **gesture patterns**.
4. Each gesture activates a corresponding **cursed technique effect**.
5. **Three.js** renders dynamic particle animations (20,000 particles).

---

## Features

- Real-time hand tracking
- Gesture-based interaction
- 3D particle effects
- Anime-inspired visual techniques
- Interactive browser experience

---

## Project Structure

jujutsu-kaisen / index.html / README.md

---

## How to Run

Clone the repository:

```bash
git clone https://github.com/YOUR-USERNAME/jujutsu-kaisen.git

Open the project folder and run:
index.html

Allow camera access when prompted.

Future Improvements
	•	Add more gesture combinations
	•	Add sound effects for techniques
	•	Improve gesture detection accuracy
	•	Mobile optimization

Author

Shivam Yadav

