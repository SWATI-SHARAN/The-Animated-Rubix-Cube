# The 3D Animated Rubik's Cube 

A fully interactive, customizable, and animated **3D Rubik's Cube** simulation built with **Three.js** for the web.

---

##  Overview

This project simulates a **realistic 3D Rubik’s Cube** with fully interactive mouse and touch controls. Users can rotate layers, solve scrambles, track their times, and personalize the look and feel of the cube with themes, animation styles, and advanced color options.

---

##  Features

###  Cube Interaction
-  Rotate full cube and individual layers with mouse/touch
-  Intuitive drag mechanics for layer turning
-  Confetti celebration on solving the cube
-  Reset and recenter camera with a single click

###  Customization
- Cube Sizes: 2x2x2 to 5x5x5
- Animation Styles: Swift, Smooth, Bounce
- Color Themes: Cube, Erno, Dust, Camo, Rain
- HSL sliders for fine-tuning each cube face color
- Perspective vs Orthographic camera toggle

###  Stats & Progress
- Built-in timer with best time tracking
- Stats panel showing solve count and averages
- Scramble generator with selectable difficulty

###  Technical Details
-  Powered by **Three.js** for WebGL rendering
-  Responsive design for mobile and desktop
-  Saves preferences and stats using **LocalStorage**
-  Modular animation engine with RAF-based updates

---

##  Controls

| Action                    | Interaction                   |
|--------------------------|-------------------------------|
| Rotate entire cube       | Click & drag anywhere         |
| Turn a layer             | Click near edge & drag        |
| Start timer              | Double-click or double-tap    |
| Reset camera             | Tap back/reset button         |
| Open Preferences         | Click on gear icon            |

---

##  Customization Options

###  Cube Sizes
- 2x2x2 – Pocket Cube
- 3x3x3 – Standard Cube
- 4x4x4 – Rubik's Revenge
- 5x5x5 – Professor's Cube

###  Color Schemes
1. **Cube** – Classic Rubik’s Cube colors
2. **Erno** – Traditional speedcube palette
3. **Dust** – Soft muted tones
4. **Camo** – Military-inspired camouflage
5. **Rain** – Bright rainbow gradient

###  Preferences Panel Includes:
- Cube size selector
- Animation style dropdown
- Scramble difficulty
- Color theme and HSL controls
- Camera mode toggle

---

##  How to Use

1. Launch the app in your browser.
2. Use mouse or touch to interact with the cube.
3. Customize via gear icon.
4. Double-tap to start solving mode.
5. Solve and get confetti celebration if completed!

---

##  Development Setup

To run the project locally:

```bash
# Clone this repository
git clone https://github.com/your-username/rubik-cube.git

# Navigate to the project directory
cd rubik-cube

# Install live-server globally (if not already installed)
npm install -g live-server

# Start the server
live-server
```

The app will be available at: `http://localhost:8080`

---

##  Dependencies

- [Three.js](https://threejs.org/) – for 3D rendering
- [Bungee Font](https://fonts.google.com/specimen/Bungee) – fun UI font
- [HTML/CSS/JS] – for structuring and interaction

---

##  Future Enhancements

- 6x6x6 and 7x7x7 cube support
- Guided solution/tutorial mode
- Move counter with algorithm display
- Save/load cube state
- Multiplayer race mode
- VR mode for immersive solving

---
