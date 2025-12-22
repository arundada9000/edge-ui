# Edge Year In Review | Precision Layout

## Overview

This project is a recreation of the mesmerizing **Edge 2025 Year in Review** UI that I encountered when I opened the Edge browser yesterday. While the review itself didn't interest me much, I was captivated by the stunning parallax background effect and interactive image cards used in the UI. Inspired by this, I decided to recreate the layout with custom designs and smooth animations.

The project features a **parallax background** with floating image cards that dynamically shift based on mouse movement. It’s built using HTML, CSS, and JavaScript, offering a unique and engaging user experience.

### Inspiration

- Inspired by Microsoft Edge – 2025 Year In Review UI

- Recreated purely for learning, experimentation, and UI exploration

## Preview

> Screenshots / previews of the UI

<p align="center"><b>Original</b></p>

![Preview 1](./preview/original.gif)

<p align="center"><b>Recreated</b></p>

![Preview 2](./preview/recreated.gif)

### Features:

- **Parallax Background**: Background shifts and responds to mouse movements with smooth transitions.
- **Dynamic Image Cards**: Cards move at different speeds for a layered parallax effect.
- **Fluid UI**: Responsive, clean layout using modern glassmorphism for a sleek design.

---

## Installation & Usage

### 1. Clone the repository:

```bash
git clone https://github.com/arundada9000/edge-ui.git
```

### 2. Open the HTML file:

Open the index.html file in any modern web browser to see the UI in action.

How It Works
HTML Structure:

#### The layout consists of:

Viewport (viewport): Contains the background which dynamically reacts to mouse movement.

Canvas (canvas): Holds image cards positioned dynamically on the screen.

#### CSS Styling:

The background uses a radial gradient which changes based on mouse movement, creating the parallax effect.

Image Cards: Positioned absolutely, they are animated with varying speeds to give depth to the scene.

Glassmorphism: The UI center uses transparent background layers and a blur effect for a modern design.

#### JavaScript Interaction:

Mousemove events calculate the mouse position and adjust both the viewport and canvas position for parallax effects.

Image cards move at different speeds based on their individual settings, creating a dynamic and immersive visual experience.

### Demo

You can check out the project in action on YouTube. I will be uploading a video demonstrating the effects and the thought process behind the design.

Original UI : https://www.microsoft.com/en-us/edge/update/year-in-review

---

### Folder structure

```
project-root/
│
├── index.html
├── preview/
│ ├── original.gif
│ ├── recreated.gif
|
└── README.md
```

## Contact

You can connect with me or reach out through any of the platforms below:

- **GitHub**: https://github.com/arundada9000
- **Instagram**: https://www.instagram.com/arundada9000
- **Facebook**: https://www.facebook.com/arundada9000
- **YouTube**: https://www.youtube.com/@arundada9000
- **WhatsApp**: +9779811420975

I’m always open to feedback, collaboration, and creative discussions.

<p align="center">
<img src="./preview/logo.png" height=150 width=150/>
</p>

### Coded for codewithease by Arun Neupane.

- _Built because the UI was too pretty to ignore._

- _Created after saying ‘wow’ to a UI one too many times._

- _Crafted with curiosity and an unhealthy love for smooth transitions._

- _I came for the review, stayed for the UI._

- _A small tribute to beautiful interfaces._

### License

- This project is open source and available under the MIT License.

### Acknowledgments

- The design was inspired by the Edge browser's 2025 Year in Review UI.

- Thanks to the community and online resources that helped make this project possible.

```
╔═╦╗╔╦╗╔═╦═╦╦╦╦╗╔═╗
║╚╣║║║╚╣╚╣╔╣╔╣║╚╣═╣
╠╗║╚╝║║╠╗║╚╣║║║║║═╣
╚═╩══╩═╩═╩═╩╝╚╩═╩═╝

⠀⠀⢀⣀⣠⣤⣤⣤⣤⣤⣤⣤⣤⣤⣤⣤⣤⣤⣤⣤⣤⣄⣀⡀⠀⠀
⠀⣴⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣦⠀
⠀⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⠀
⢰⣿⣿⣿⣿⣿⣿⣿⣿⣿⡟⠻⢿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡆
⢸⣿⣿⣿⣿⣿⣿⣿⣿⣿⡇⠀⠀⠈⠛⠿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡇
⢸⣿⣿⣿⣿⣿⣿⣿⣿⣿⡇⠀⠀⠀⠀⠀⢈⣹⣿⣿⣿⣿⣿⣿⣿⡇
⢸⣿⣿⣿⣿⣿⣿⣿⣿⣿⡇⠀⠀⢀⣤⣶⣿⣿⣿⣿⣿⣿⣿⣿⣿⡇
⠸⣿⣿⣿⣿⣿⣿⣿⣿⣿⣧⣴⣾⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⠇
⠀⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⠀
⠀⠻⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⠟⠀
⠀⠀⠈⠉⠙⠛⠛⠛⠛⠛⠛⠛⠛⠛⠛⠛⠛⠛⠛⠛⠛⠋⠉⠁⠀⠀
```
