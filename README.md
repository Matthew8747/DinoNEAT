# Chrome Dino AI using NEAT

This project implements an AI to play the Chrome offline Dinosaur game using the NEAT (NeuroEvolution of Augmenting Topologies) algorithm. The AI trains itself to improve its performance over generations, learning to jump over obstacles efficiently.

## Features
- Uses the **NEAT algorithm** to evolve a neural network for controlling the dinosaur.
- Implemented in **Python** using **Pygame** for game simulation.
- Dynamic difficulty adjustment: the game speed increases as the AI plays.
- Visual representation of AI decision-making with hitboxes and obstacle tracking.

## Installation
### Prerequisites
Ensure you have Python installed (version 3.x recommended). Install dependencies using:
```bash
pip install pygame neat-python
```

### Running the AI
Clone the repository and navigate to the project folder:
```bash
git clone https://github.com/yourusername/chrome-dino-neat.git
cd chrome-dino-neat
```
Run the script:
```bash
python dino_ai.py
```

## How It Works
1. **Game Simulation**: The game is recreated using Pygame, including the dinosaur, obstacles, and background.
2. **Neural Network Training**: Each dinosaur (AI agent) is controlled by a neural network evolved using NEAT.
3. **Fitness Evaluation**: Dinosaurs are rewarded for surviving longer and penalized for colliding with obstacles.
4. **Evolution**: The best-performing networks are selected and evolved over multiple generations to improve performance.

## Configuration
The NEAT configuration settings are stored in `config.txt`. You can adjust parameters like population size, mutation rates, and network structure to optimize learning. Parameters used in the demo are the same in current config

## Demo
![Dino AI Demo](Assets\dinoDemo.gif)

## Future Improvements
- Implement reinforcement learning for more advanced decision-making.
- Add more complex obstacles and environmental variations.
- Train on different difficulty levels and introduce adaptive learning.
