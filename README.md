# ✦ STARGLIDE – Gesture-Controlled Space Survival

<p align="center">
  <img src="screenshot.png" alt="STARGLIDE" width="700">
</p>

STARGLIDE is a high-performance, browser-based space shooter that merges traditional arcade mechanics with real-time computer vision. Instead of relying on a keyboard or mouse, players pilot their spacecraft and engage cosmic threats entirely through hand gestures captured via webcam.

## 🚀 Live Demo
👉 **[[https://star-glide.netlify.app/]]**

---

## 🛠️ Tech Stack & Architecture

*   **Computer Vision:** Powered by Google's MediaPipe Tasks-Vision (`HandLandmarker`) utilizing local WebGL GPU delegation for latency-free hand tracking.
*   **Graphics & Rendering:** Built entirely with a custom HTML5 Canvas engine implementing an optimized dynamic game loop, real-time particle mechanics, screen-shaking, and vector math.
*   **State Management & Persistence:** Local storage integration (`localStorage`) ensures player progression, statistics, ship upgrades, and trophy achievements persist across browser sessions.
*   **Styling:** A futuristic, responsive deep-space aesthetic designed using tailored glassmorphism principles and monochrome ambient-breathing HUD animations.

---

## ✦ Key Features

*   **Immersive Hand Tracking:** Fly and steer your ship organically using an open palm (`✋`). Close your hand into a fist (`✊`) to initiate a weapon-firing sequence. 
*   **Hangar Progression System:** Spend collected stars to purchase or max-upgrade 4 distinct starships (Aether Wing, Steel Citadel, Crimson Phantom, Nebula Phantom), each scaling its own fire rate, laser array pattern, and cooldowns.
*   **Unique Ultimate Abilities:** Unleash tactical ship-specific screen wipes, hyper lasers, 360° death blossoms, or invulnerability rams when your ultimate meter is charged.
*   **5-Phase Escalating Boss Encounters:** Battle distinct flagship bosses (from the Aegis Juggernaut to the Oblivion Monarch) featuring complex projectile tracking, custom movement behaviors, and multi-layered attack patterns.
*   **Monochrome UI System:** Features an elegant, modern, deeply frosted camera permission overlay utilizing minimalist CSS-engineered ambient breathing effects to fit a premium sci-fi aesthetic.
*   **Adaptive Audio:** Integrated background music loops paired with custom real-time oscillator frequencies (`AudioContext`) for sound effects, complete with pause-menu mute toggles and standalone menu volume controls.
*   **Dynamic Difficulty Scaling:** Choose between Easy, Medium, and Hard modes to scale asteroid spawn density, collision speeds, and aggressive boss AI variables.
*   **In-Game Trophy System:** A persistent 22-tier achievement tracker that triggers slide-in reward notifications based on specific distance milestones, total asteroid destruction counts, and battle performance.

---

## 📦 Local Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/Soumya7008-lab/starglide.git](https://github.com/Soumya7008-lab/starglide.git)
