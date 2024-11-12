
# **Cosmic Heat: A 2D Space Shooter Game**

## **Aim**
The aim of this project is to develop a 2D space shooter game, **Cosmic Heat**, using Python and Pygame. This game combines classic arcade shooting mechanics with modern AI techniques to create an engaging gameplay experience. Players control a spaceship using either the keyboard or a joystick to fight through waves of enemies and challenging boss battles. The AI techniques are implemented to enhance enemy behavior and make each encounter dynamic and challenging.

### Step-by-Step Algorithm

1. **Start the Program**
   - Initialize the Python environment.
   - Import required libraries, including `pygame` for game graphics and controls, and other necessary AI and math libraries.

2. **Initialize Pygame and Game Settings**
   - Set up the Pygame display window with a specific width and height.
   - Define variables for game assets such as background, player ship, enemies, bosses, and sounds.
   - Define constants for game parameters such as screen dimensions, player speed, bullet speed, enemy speed, etc.

3. **Define Player and Enemy Classes**
   - Create a `Player` class with attributes for position, speed, health, and methods for movement and shooting.
   - Create an `Enemy` class to handle enemy attributes and actions, using AI techniques to define behavior.

4. **Implement AI Algorithms for Enemy Behavior**
   - **Finite State Machines (FSMs)**: Set up states like patrolling, attacking, and retreating, and specify transitions between these states based on player proximity and health.
   - **Pathfinding (A* Algorithm)**: Implement A* or similar algorithm for enemy movement, especially for bosses, allowing them to navigate toward the player while avoiding obstacles.
   - **Rule-Based Systems**: Define rules for simple enemy actions like shooting when within range, moving in specific patterns, or idling.
   - **Dynamic Difficulty Adjustment (DDA)**: Set up a mechanism to track player performance and dynamically adjust spawn rates and enemy behavior accordingly.

5. **Game Loop**
   - **Start the Game Loop**: Begin a continuous game loop to update gameplay elements.
   - **Check for Player Input**: Capture player keyboard or joystick input for moving the ship, shooting, pausing, or exiting the game.
   - **Update Player Position**: Adjust player position based on input.
   - **Update Enemy and Boss Behavior**: Use AI algorithms to change enemy positions, select targets, and update attack patterns.
   - **Collision Detection**: Check for collisions between player bullets and enemies, as well as enemy bullets and the player. If a collision occurs, adjust health or remove the enemy.
   - **Adjust Difficulty Dynamically**: Monitor player performance and adjust spawn rates, enemy health, or speed to match the player's skill level.
   - **Draw Elements**: Render the background, player, enemies, bullets, and other UI elements onto the screen.
   - **Update Display**: Refresh the Pygame display with updated game state visuals.

6. **Check for Game Over Condition**
   - If the player's health reaches zero, end the game.
   - Display a game-over message and offer an option to restart or exit.

7. **Quit the Game**
   - Stop the game loop and close the Pygame window upon exit.
  

## **Game Launch**

1. **Clone the repository**:  
   ```bash
   git clone https://github.com/manojvenaram/Cosmic-Heat-A-2D-Space-Shooter-Game.git
   ```
   
2. **Navigate to the project directory**:  
   ```bash
   cd cosmic-heat-pygame
   ```

3. **Install the required packages**:  
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the game**:  
   ```bash
   python main.py
   ```

## **Controls**

- **Shoot**: Press `SPACE`
- **Move**: Use `Arrow keys`
- **Pause**: Press `P`
- **Exit**: Press `Esc`

## **Gameplay Screenshot**

Below are some gameplay screenshots showing different stages and enemy encounters.
![image](https://github.com/user-attachments/assets/b7068efd-792a-42d9-adc9-b12d5537fd77)

![image](https://github.com/user-attachments/assets/2630ad5b-e9b1-4d2f-87d8-2ed2aebae866)
![image](https://github.com/user-attachments/assets/0e02414d-20ee-4845-bb0f-4e07a9e563c0)
![image](https://github.com/user-attachments/assets/70a45755-fcfa-4d54-9b0b-dec07bde99a4)
![image](https://github.com/user-attachments/assets/a62ee6c6-42f9-456e-b6f4-00519be1ac78)




## **Results**

The game successfully uses AI techniques to enhance gameplay, with enemies that change behavior based on the player’s actions. FSMs allow for structured state changes, and rule-based systems provide basic but effective enemy reactions. The pathfinding and dynamic difficulty adjustments make boss battles more challenging, adjusting gameplay complexity as the player progresses.
