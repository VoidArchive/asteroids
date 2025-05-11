# Pygame Asteroids Clone

## Project Overview

This is a classic Asteroids game clone built using Python and the Pygame library. The primary goal of this project was to learn and apply game development fundamentals, including:

* Object-oriented programming for game entities (Player, Asteroids, Bullets)
* Handling user input for player movement and actions
* 2D vector math for motion and rotation
* Collision detection
* Game state management (e.g., gameplay, game over)
* Basic game loop structure
* Rendering graphics and text to the screen

This project was developed as part of the [Build an asteroids game using pygame](https://www.boot.dev/courses/build-asteroids-python) curriculum on **Boot.dev**.

## Gameplay

* **Objective:** Survive as long as possible by destroying asteroids and avoiding collisions.
* **Controls:**
  * **Up Arrow / W:** Thrust forward
  * **Left Arrow / A:** Rotate counter-clockwise
  * **Right Arrow / D:** Rotate clockwise
  * **Spacebar:** Shoot bullets
* **Features:**
  * Player-controlled spaceship
  * Asteroids of varying sizes that break into smaller pieces when shot
  * Bullets fired by the player
  * Screen wrapping (entities that go off one side reappear on the opposite)
  * (Optional: Add score, lives, game over screen if you implemented them)

## Technologies Used

* **Python 3.x**
* **Pygame 2.x**

## Setup and Installation

1. **Ensure Python is installed:**
    You can download Python from [python.org](https://www.python.org/).

2. **Install Pygame:**
    Open your terminal or command prompt and run:

    ```bash
    pip install pygame
    ```

3. **Clone the repository (or download the files):**

    ```bash
    # If you have this on GitHub
    # git clone <repository_url>
    # cd <repository_name>
    ```

    If you just have the files locally, navigate to the directory containing `main.py` (or your main game file).

4. **Run the game:**

    ```bash
    python main.py
    ```

    (Replace `main.py` with the actual name of your main game script if it's different.)

## Lessons Learned (from Boot.dev course)

* Understanding and implementing the Pygame game loop.
* Using `pygame.Vector2` for positions, velocities, and directions.
* Creating and managing game objects (Sprites or custom classes).
* Handling keyboard input for real-time interaction.
* Implementing collision detection (e.g., circle-to-circle).
* Basic sprite animation and rotation.
* Drawing shapes, images, and text on the screen.
* Structuring a game into logical components.

## Future Improvements

* Score tracking and display
* Player lives system
* Game Over and Start screens
* Sound effects and background music
* Different types of enemies or power-ups
* Improved graphics and animations

## Acknowledgements

* **Boot.dev** for the excellent course and guidance.
* The Pygame community for the powerful and easy-to-use library.

---

Happy Gaming!
