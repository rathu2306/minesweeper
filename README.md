````markdown
#Minesweeper with Knowledge-Based AI

A classic Minesweeper game implemented in Python with Pygame, featuring an intelligent AI agent that uses knowledge representation and first-order logic to play the game strategically.

---

##Table of Contents

- [Overview](#overview)  
- [Features](#features)  
- [AI Agent](#ai-agent)  
- [Installation](#installation)  
- [Usage](#usage)  
- [Controls](#controls)  
- [Project Structure](#project-structure)  
- [License](#license)

---

## Overview

This Minesweeper implementation delivers a smooth gameplay experience with an interactive graphical interface. The standout feature is the AI agent, which leverages formal logic and knowledge-based reasoning to deduce safe moves and flag mines, reducing guesswork typically involved in the game.

Built with Python and Pygame, the project serves as both an engaging game and an educational tool demonstrating core AI concepts such as inference, knowledge representation, and reasoning under uncertainty.

---

## Features

- **Classic Minesweeper Gameplay:** 8x8 grid with 8 hidden mines.  
- **Interactive Interface:** Click cells to reveal or flag them; clear visual indicators for mines, flags, and numbers.  
- **Knowledge-Based AI Agent:**  
  - Uses **first-order logic** and a **dynamic knowledge base** to infer safe cells and mines.  
  - Makes moves based on logical deduction rather than blind guessing.  
  - Falls back on probabilistic/random moves only when no safe move can be inferred.  
- **Game States:** Real-time feedback on win/loss.  
- **User-Friendly UI:** Instructions screen, reset and AI move buttons.  

---

## AI Agent

The AI agent is designed around **knowledge-based reasoning** principles, applying:

- **Knowledge Representation:** Maintaining a set of logical statements describing which cells are safe or contain mines.  
- **Inference via First-Order Logic:** Using revealed information and game rules to deduce the status of unrevealed cells.  
- **Dynamic Learning:** Continuously updates its knowledge base after each move to refine its understanding of the board.  
- **Decision-Making:** Chooses moves that are guaranteed safe whenever possible, dramatically reducing risk and guesswork.  
- **Fallback Strategy:** When logical inference fails to find safe moves, it intelligently makes random moves to progress the game.

This AI approach showcases fundamental concepts in artificial intelligence and demonstrates how logic and knowledge can be applied to complex decision-making problems.

---

## Installation

1. Clone the repository:  
   ```bash
   git clone https://github.com/yourusername/minesweeper-ai.git
   cd minesweeper-ai
````

2. Create a virtual environment (optional but recommended):

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

---

## Usage

Run the game with:

```bash
python runner.py
```

This will launch the Pygame window where you can play Minesweeper or watch the AI solve it step-by-step.

---

## Controls

* **Left-click:** Reveal a cell.
* **Right-click:** Flag or unflag a cell as a mine.
* **AI Move Button:** Let the AI make its next logical move.
* **Reset Button:** Restart the game.

---

## Project Structure

```
minesweeper-ai/
├── assets/
│   ├── fonts/
│   │   └── OpenSans-Regular.ttf
│   └── images/
│       ├── flag.png
│       └── mine.png
├── minesweeper.py       # Game logic and AI implementation
├── runner.py            # Main game loop and UI rendering
├── requirements.txt     # Python dependencies (pygame)
└── README.md            # This file
```

---

## License

CS50 

---

Feel free to contribute, report bugs, or suggest improvements!

```

---
```
