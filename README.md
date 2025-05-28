Got it! Here's a polished, professional README in markdown for your Minesweeper project — clear, concise, and well-structured:

````markdown
# Minesweeper with AI — Pygame Implementation

A classic Minesweeper game built with Python and Pygame, enhanced with an AI agent that assists with gameplay by suggesting and making moves. 

---

## Table of Contents

- [Overview](#overview)  
- [Features](#features)  
- [Installation](#installation)  
- [Usage](#usage)  
- [Controls](#controls)  
- [Project Structure](#project-structure)  
- [Dependencies](#dependencies)  
- [Contributing](#contributing)  
- [License](#license)  

---

## Overview

This project recreates the timeless Minesweeper game using Pygame for the GUI and Python for the core logic. The game supports both manual user interaction and AI-driven moves, offering an engaging and educational experience in AI-assisted gameplay.

---

## Features

- **8x8 Board** with 8 hidden mines.  
- **User Interaction**: Left-click to reveal cells, right-click to flag/unflag mines.  
- **AI Agent**: Performs safe moves or random moves when no safe moves are known.  
- **Visual Feedback**: Mines, flags, and mine counts are clearly displayed.  
- **Game States**: Clear indicators for win/loss conditions.  
- **Intuitive UI**: Instruction screen and interactive buttons for AI move and game reset.  

---

## Installation

### Prerequisites

- Python 3.7 or higher  
- [Pygame](https://www.pygame.org/news)

### Steps

1. Clone the repository or download the source code.

2. Install dependencies via pip:

   ```bash
   pip install -r requirements.txt
````

3. Ensure the `assets` folder (containing fonts and images) is in the project root:

   ```
   assets/
     fonts/
       OpenSans-Regular.ttf
     images/
       flag.png
       mine.png
   ```

---

## Usage

Run the game using:

```bash
python runner.py
```

This will launch the Minesweeper window with instructions. Click **Play Game** to start.

---

## Controls

| Action           | Input                    |
| ---------------- | ------------------------ |
| Reveal Cell      | Left Mouse Click         |
| Flag/Unflag Cell | Right Mouse Click        |
| Trigger AI Move  | Click **AI Move** button |
| Reset Game       | Click **Reset** button   |

---

## Project Structure

```
├── runner.py          # Main game loop and UI rendering
├── minesweeper.py     # Core game logic and AI agent
├── assets/
│   ├── fonts/
│   │   └── OpenSans-Regular.ttf
│   └── images/
│       ├── flag.png
│       └── mine.png
├── requirements.txt   # Python dependencies
└── README.md          # Project documentation
```

---

## Dependencies

* **pygame** — For graphical interface and event handling.

---

## Contributing

Contributions, issues, and feature requests are welcome! Feel free to fork the repository and submit pull requests.

---

## License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.

---

## Contact

For questions or suggestions, please reach out or open an issue in the repository.

---

Enjoy playing and learning Minesweeper with AI assistance!

```
