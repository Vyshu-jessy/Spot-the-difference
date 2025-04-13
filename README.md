 Spot the Difference Game

A simple interactive **“Spot the Difference”** game built with HTML, CSS, JavaScript, and JSON configuration. Deployed live using Vercel.

 Game Description

Two images are displayed side by side. Your task is to find all the differences between them by clicking on the image areas where they differ.

Each correct click:
- Highlights the found difference
- Increases your score
- Brings you closer to winning!

The game also includes:
- A live timer ⏱
- Mobile-friendly layout 📱
- JSON-based configuration for easy level changes



Project Structure

text
 Spot-the-difference/
│
├── index.html              ← Main game file
├── style.css               ← Optional external CSS
├── script.js               ← Optional external JavaScript
├── game-config.json        ← Contains image paths & difference coordinates
├── /images                 ← Folder for your game images
└── README.md               ← This file
JSON Configuration
The game uses a game-config.json file to load levels dynamically.

Example Structure:
json
Copy code
{
  "gameTitle": "Spot the Difference - Animals",
  "images": {
    "image1": "images/image1.jpg",
    "image2": "images/image2.jpg"
  },
  "differences": [
    { "x": 100, "y": 200, "width": 50, "height": 50 },
    { "x": 300, "y": 150, "width": 40, "height": 40 },
    { "x": 500, "y": 300, "width": 30, "height": 30 }
  ]
}
Just update this JSON to change the level — no need to touch the JavaScript code!

How to Run Locally
Make sure you have Python installed.

Navigate to the project folder in your terminal.

Run a local server:



Copy code
python -m http.server
Open your browser and visit:
http://localhost:8000

Live Demo
Play the game here:
https://spot-the-difference-delta.vercel.app

SCREENSHOTS:
bash![Screenshot 2025-04-13 164902](https://github.com/user-attachments/assets/6079bcac-b973-424c-97a0-3ca9b07694c9)
![Screenshot 2025-04-13 164937](https://github.com/user-attachments/assets/e287462a-d6b8-444b-84ba-a35250949ad0)
![Screenshot 2025-04-13 164957](https://github.com/user-attachments/assets/8512993f-a9f7-4100-9899-47db8ddc3e57)
![Screenshot 2025-04-13 165011](https://github.com/user-attachments/assets/8380c7d3-8398-461e-af83-224f![Screenshot 2025-04-13 165021](https://github.com/user-attachments/assets/2bb0c84d-d49f-495b-b109-7552c9945cd9)
a2cd3d3c)

 Credits
Created by Vyshu Jessy
Deployed using Vercel

