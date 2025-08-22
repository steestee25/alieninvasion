# Alien Invasion

A **2D arcade-style shooter game** built with **Python** and **Pygame**, inspired by classic space invader games. Players control a spaceship to shoot down fleets of aliens before they reach the bottom of the screen.

---

## 🎥 Gameplay Preview

Want to see Alien Invasion in action? Here's a quick look at the gameplay:

https://github.com/user-attachments/assets/209e6696-73f4-45e6-be73-1517e3097cef

*The GIF above shows a sample playthrough, including shooting aliens, scoring, and level progression.*

---

## 🚀 **Project Overview**

Alien Invasion is a fully playable game developed as part of learning game development fundamentals. It includes:

* Responsive player controls (keyboard and mouse input).
* Animated elements like bullets and alien fleets.
* Game state tracking with scoring, lives, and levels.
* Dynamic difficulty progression as the player advances.
* Interactive UI with Play button and instructions.

---

## 🛠 **Technologies & Libraries Used**

* **Programming Language**: [Python 3](https://www.python.org/)
* **Game Library**: [Pygame](https://www.pygame.org/)
* **Additional Concepts**:

  * Object-Oriented Programming (OOP) principles
  * Event handling and collision detection
  * Code refactoring for scalability

---

## 🎮 **Game Functionalities**

### Core Features

1. **Spaceship Controls**:

   * Move left and right with keyboard input.
   * Fire bullets to destroy aliens.

2. **Alien Fleet Mechanics**:

   * Fleet generation using nested loops.
   * Aliens move as a group and change direction when reaching screen edges.
   * Collision detection for bullets hitting aliens and aliens colliding with the ship.

3. **Game Progression**:

   * Progressive difficulty (game speed increases each level).
   * Scoring system with a display for current and high scores.
   * Game over and restart mechanics using a **Play button**.

4. **User Interface Enhancements**:

   * Mouse-based interaction for Play button.
   * Cursor hidden during active gameplay for immersion.
   * Textual and graphical feedback on the screen.

---

## 📈 **Useful Concepts Experienced**

* **Clean OOP Architecture**: Code is modular, with separate classes for settings, ship, bullets, aliens, and game stats. This makes the project easy to maintain and expand.
* **Event-Driven Design**: Usage of event loops, input handling, and collision logic.
* **Refactoring & Code Quality**: Regular refactoring applied for better readability and future development.
* **UI/UX Considerations**: Interactive Play button, scoreboards, and visual feedback enhance user experience.

---

## 🏁 **How to Run the Game**

1. Install Python (3.8 or later recommended).
2. Install Pygame:

   ```bash
   pip install pygame
   ```
3. Clone this repository:

   ```bash
   git clone https://github.com/steestee25/alieninvasion.git
   cd alien_invasion
   ```
4. Run the game:

   ```bash
   python alien_invasion.py
   ```

