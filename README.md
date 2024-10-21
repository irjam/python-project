# python-project
# Fighting Game Project

## Project Description
This project is a 2D fighting game developed using Python's Pygame library. Players can choose from various fighters and engage in combat in dynamic arenas, featuring unique backgrounds and animations.

## Implemented Functionality
- Character Selection: Players can select their fighters through a graphical interface.
- Combat Mechanics: Fighters can move, attack, and display health bars.
- Sound Effects: Background music and sound effects enhance the gaming experience.
- Visuals: Dynamic backgrounds and animated sprites provide an engaging visual experience.

## Architecture
The project will be structured into several classes and functions:
- Classes:
  - Player: Manages player input and interactions.
    - Methods: draw(), update_selection()
  - Fighter: Handles fighter attributes and actions.
    - Attributes: health, position, animation_steps
    - Methods: move(), update(), draw()
  - Intro: Manages introductory screens and transitions.
    - Methods: display()
  
- Functions:
  - Music(): Handles background music and sound effects.
  - Player_Choosing(): Manages the fighter selection screen.
  - draw_health_bar(): Visual representation of fighter health.
