# Don’t Find Me — 15-112 Term Project (Python/Tkinter)

Minimalist evasion game where you dodge detection, score points in short replayable rounds, and try to outlast increasingly tricky patterns. Built as a CMU 15-112 term project; the repo contains multiple TP milestones, with the latest at TP3.12/. 
GitHub
+1

🎥 Demo video: Python Tkinter game made by Mario Belmonte: “Don’t find me” — YouTube

## Features

- Fast, focused gameplay: short rounds, quick restarts, clean start → play → game-over flow.

- Tight controls & collision checks: responsive movement with frame-based updates for smooth motion.

- Clear game states & UI: on-canvas text for menus, score, and feedback; no external assets required.

- Pure-Python desktop build: runs with standard Tkinter (no browser or game engine).

Tip: The repository tracks iterations from TP0 up through TP3.12; the final submission folders make it easy to compare progression over time. 
GitHub

## Getting Started
### Prerequisites

- Python 3.9+

- Tkinter (bundled with most Python installers on macOS/Windows; on some Linux distros install python3-tk)

### Clone
    git clone https://github.com/Qrytics/15-112-Term-Project.git
    cd 15-112-Term-Project/TP3.12

### Run
    python3 main.py


If your entry file is named differently (e.g., termProject.py), update the command accordingly.

## How to Play

- Move: Arrow keys (or WASD)

- Goal: Avoid being “found” as long as possible.

- Score: Survive longer / complete round objectives to increase score.

- Restart: Press R (from game-over) or follow on-screen prompt.

(Adjust the key names above if you customized bindings in code.)

## Project Structure
15-112-Term-Project/

    ├── TP0/            initial scaffold

    ├── TP1.5/          early prototype

    ├── TP1.9/          incremental milestones

    └── TP3.12/         final deliverable (run from here)

        ├── main.py
    
        ├── /src game   logic modules (entities, states, utils)
    
        └── /assets     optional fonts/sounds if used


Folder names reflect standard 15-112 TP milestones; open TP3.12 for the latest version. 
GitHub

## Technical Notes

- GUI: Tkinter Canvas with a fixed timestep game loop for deterministic updates.

- Design: small modules (entities, collisions, state machine) to keep logic readable.

- Performance: integer or pixel-space math to avoid float drift; lightweight redraw regions.

## Roadmap / Ideas

- Difficulty curves (adaptive speed, patterns)

- Sound effects + simple hit/lose cues

- High-score persistence (JSON file)

- Optional controller support (via inputs/pygame if allowed)

## Contributing

Issues and PRs welcome. Please keep changes self-contained to TP3.12/ and include a short gif or screen recording when touching gameplay.

## Credits

Author: Mario Belmonte

Course: 15-112 Fundamentals of Programming & Computer Science

Demo: YouTube – Don’t Find Me
