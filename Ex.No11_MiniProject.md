
# **Cosmic Heat: A 2D Space Shooter Game**

## **Aim**
The aim of this project is to develop a 2D space shooter game, **Cosmic Heat**, using Python and Pygame. This game combines classic arcade shooting mechanics with modern AI techniques to create an engaging gameplay experience. Players control a spaceship using either the keyboard or a joystick to fight through waves of enemies and challenging boss battles. The AI techniques are implemented to enhance enemy behavior and make each encounter dynamic and challenging.

## **Algorithms and AI Techniques**

The following algorithms are used to develop intelligent enemy and boss behaviors in **Cosmic Heat**:

### 1. **Finite State Machines (FSMs)**
   - **Purpose**: Manage enemy states, such as patrolling, attacking, or retreating.
   - **Implementation**: Each enemy has predefined states and transitions between them based on certain conditions (e.g., proximity to the player or current health).
   - **Effect**: Enables enemies to behave dynamically, adapting their actions depending on the player’s movements.

### 2. **Pathfinding (A* Algorithm)**
   - **Purpose**: Used to guide enemy movement patterns, especially for larger or boss enemies that may need to navigate around obstacles.
   - **Implementation**: While space shooters traditionally have linear movement, pathfinding introduces adaptability, especially in boss phases, allowing enemies to adjust paths dynamically.
   - **Effect**: Provides a more engaging and challenging experience as enemies and bosses alter their movements to target the player.

### 3. **Rule-Based Systems**
   - **Purpose**: Simple logic-based system for basic enemy behaviors.
   - **Implementation**: Rules are defined based on player actions. For instance, if the player is within a certain range, the enemy will shoot; otherwise, it may idle or move.
   - **Effect**: Ensures consistent enemy behavior, simplifying movement and attack decisions to create diversity in gameplay.

### 4. **Dynamic Difficulty Adjustment (DDA)**
   - **Purpose**: Adjusts game difficulty dynamically based on the player’s skill level.
   - **Implementation**: Modifies enemy spawn rates and increases boss difficulty based on player’s performance metrics like health or score.
   - **Effect**: Keeps gameplay engaging by providing a challenge proportional to the player’s skill level.

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
