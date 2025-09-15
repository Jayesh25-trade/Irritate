# IrritateMe – The Day After Calculator

## Overview
**IrritateMe** is a playful, gamified web application that tells you what day it will be after a given number of days. Instead of providing an instant result, the app challenges users to complete a series of interactive puzzles and mini-games before revealing the answer.

This project combines humor, patience-testing mechanics, and simple browser-based games to create a unique user experience.

## Features
- **Input Screen**: Users enter a number of days (X) to calculate.
- **Loading Screen**: Fake but entertaining loading messages simulate “serious computations.”
- **Maze Puzzle**: Navigate through a randomly generated maze to progress.
- **Word Search Puzzle**: 
  - Answer a quiz correctly to reveal a key word.  
  - Find the word in a dynamically generated alphabet grid.  
  - Includes a countdown timer and a hidden “scare” effect for added suspense.
- **Checkbox Garden**: 
  - Hundreds of checkboxes hide the correct choice.  
  - Players get 5 attempts with hints and proximity feedback (color-coded).  
- **Final Reveal**: Displays the correct future day of the week with a humorous roast message.
- **Sound Effects**: Lightweight sound effects for feedback.
- **Confetti Reward**: A celebratory animation when challenges are completed.

## Technology Stack
- **Frontend**: HTML5, CSS3, Vanilla JavaScript
- **Canvas API**: For maze generation and rendering
- **Media**: Custom video overlay for scare effect
- **Version Control**: Git & GitHub

## Installation & Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/Jayesh25-trade/Irritate.git
   cd Irritate
Irritate/
├── index.html
├── assets/
│   └── scare.mp4
├── .gitignore
└── README.md
Place your horror video file inside the assets/ folder and rename it to scare.mp4.

- Open the project:

- Simply open index.html in any modern browser.


**Usage**

- Enter the number of days in the input field.

- Progress through all challenges (maze, word search, and checkbox garden).

- The application reveals the day of the week after the given number of days.
