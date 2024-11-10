# Fuzzy Logic Snake Game

A classic Snake game implemented with fuzzy logic for more advanced control. In this game, the snake navigates an arena to eat food items, which lengthen its body. The goal is to avoid colliding with the snake's own body or any obstacles like fire blocks that may be present. 

This game allows the user to switch between manual control and automated fuzzy logic-based controllers, each optimized for different layouts of obstacles.

## About Fuzzy Logic

Fuzzy logic is a form of logic used to handle uncertainty and approximate reasoning, mimicking the way humans make decisions. Instead of rigid true/false values, fuzzy logic operates with degrees of truth, allowing for more flexible and human-like decision-making. In this Snake game, fuzzy logic is used to determine the snake's next move based on factors like its proximity to food, its own body, and obstacles. This approach enables a more sophisticated and adaptive gameplay experience, especially at higher difficulty levels.

## Features

- **Manual Controller**: Control the snake with arrow keys.
- **Crisp Rules Controller**: Automated controller using basic crisp rules.
- **Fuzzy Rules Controller**: Advanced fuzzy logic controller optimized for maneuvering through obstacles.
- **Levels with Varying Difficulty**: No bricks, vertical bricks, horizontal bricks, and inverted L-shaped bricks layouts.

## Game Levels

1. **No Bricks Level** (`0`): The snake's only threat is self-collision, ideal for beginners.
2. **Vertical Bricks Level** (`1`): Bricks are arranged in a vertical pattern, posing an obstacle to avoid.
3. **Horizontal Bricks Level** (`2`): Bricks are laid out horizontally.
4. **L-Shaped Bricks Level** (`3`): Bricks are arranged in an inverted L shape, making it the hardest level.

## Game Controllers

1. **Manual Controller** (`0`): Control the snake with arrow keys.
2. **Crisp Rules Controller** (`1`): Baseline controller using crisp rules.
3. **Fuzzy Rules Controller** (`2`): Uses fuzzy logic for better navigation.
4. **Fuzzy Rules Controller for Bricks** (`3`): Optimized fuzzy logic specifically to avoid brick collisions.

## Contributors
1. Vinayak Goyal 2201AI52
2. Saksham Singh 2201AI33
3. Tanay Chhajed 2201ai39
4. Harsh Kumar 2201ai14
5. Shubhanshi Bishnoi 2201ai53
## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/fuzzy-logic-snake-game.git
    cd fuzzy-logic-snake-game
    ```

2. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

Run the game with different controllers and levels using the following command:

```bash
python App.py [controller] [level]
