# Hypercube Havoc  
*A 4D-Inspired Brick Challenge*

---

## 🎮 About The Game  
Hypercube Havoc is an innovative single-page JavaScript game that simulates interaction within a tesseract-like structure, visualized as distinct “slices” or “layers” in 3D space using Three.js. Players observe four uniquely colored striker balls, each operating within its own dimensional slice of a larger “hyper-brick” assembly. The objective is to “claim” bricks by changing their color upon collision, racking up scores for each of the four dimensions/colors.

The game features AI-powered commentary and a creative naming feature for in-game patterns, adding a unique layer of engagement!

---

## ✨ Features  
- **4D-Inspired Gameplay**  
  Experience action across four parallel 3D “W-slices” stacked vertically, representing a conceptual 4th dimension.  

- **Dynamic Brick Interaction**  
  - Four colored balls (Red, Green, Blue, Yellow) move randomly within their assigned W-slices.  
  - Balls recolor bricks they collide with (if different), scoring points for their color.  
  - Balls phase through same-colored bricks.  

- **W-Slice Transitions**  
  Balls can pass through the X and Z faces of their current W-slice to enter adjacent slices, adding chaotic movement.  

- **Multiple Camera Views**  
  - **Observer View:** Strategic overview of the entire hypercube with orbit controls.  
  - **Ball Cameras:** Chase each of the four balls in real time.  

- **AI-Powered Features (via Gemini API)**  
  - **Hyper-Commentator:** Witty AI commentary every 20 seconds.  
  - **Name This Chaos!:** Generate a creative name for the current brick pattern.  

- **Scoring System**  
  Tracks scores for each of the four colors based on bricks claimed.  

- **Sound Effects**  
  Unique tones (via Tone.js) when balls claim bricks.  

- **Interactive UI**  
  - Scoreboard for all four colors  
  - View-selection dropdown  
  - “Reset” and “✨ Chaos Name” buttons  
  - Status updates for sound and AI features  

- **Responsive Design**  
  The 3D scene and UI adapt to different window sizes.

---

## 🕹️ How to Play  
1. **Open the Game**  
   - Open `index.html` (or `hypercube_havoc.html`) in any WebGL-capable browser (Chrome, Firefox, Edge, Safari).  
2. **Enable Sound**  
   - Click the canvas to activate sound effects.  
3. **Observe the Chaos**  
   - Watch four colored balls move through their W-slices, recoloring bricks and slicing through dimensions.  
4. **Switch Camera Views**  
   - Use the “View” dropdown in the top-right UI.  
   - **Observer View:**  
     - Orbit: Left-click & drag  
     - Pan: Right/middle-click & drag  
     - Zoom: Scroll wheel  
   - **Ball Views:** Follow individual balls up close.  
5. **Use AI Features**  
   - **Hyper-Commentator:** Auto remarks every 20 seconds.  
   - **✨ Chaos Name:** Click to get an AI-generated pattern name.  
6. **Reset**  
   - Click “Reset” to restart scores and layout.

---

## 🛠️ Technologies Used  
- **HTML5 & CSS3** (Tailwind CSS)  
- **JavaScript (ES6 Modules)**  
- **Three.js** — 3D rendering  
- **Tone.js** — Sound effects  
- **Gemini API** — AI commentary & naming  

---

## 🚀 Setup & Installation  
1. Download the single HTML file (e.g., `hypercube_havoc.html`).  
2. Open it directly in your browser.  
3. Ensure an internet connection for Gemini API features.  
4. No build steps or dependencies required.

---

## 🔮 Future Enhancements  
- **Player Interaction:** Subtle control over ball paths or power-ups.  
- **Advanced 4D Transitions:** “Folding” effects or portals between slices.  
- **Levels & Objectives:** Specific pattern goals or challenges.  
- **Visual Customization:** Themes, brick styles, ball skins.  
- **Expanded AI:**  
  - AI-generated objectives or mini-quests.  
  - Analysis of “lucky” or “unlucky” movements.

Enjoy the chaotic beauty of **Hypercube Havoc!**  
