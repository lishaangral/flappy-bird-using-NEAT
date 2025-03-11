# Flappy Bird: NEAT-Driven Evolutionary Game Simulation  

This repository contains an AI-powered self-learning agent that autonomously plays Flappy Bird using **NeuroEvolution of Augmenting Topologies (NEAT)**. The AI evolves strategies dynamically, improving its performance over multiple generations through reinforcement learning techniques.  

![Flappy Bird Using NEAT](./imgs/flappy_bird.png)

## Table of Contents  
- [Introduction](#introduction)  
- [Features](#features)  
- [Live Demo](#live-demo)  
- [Technologies Used](#technologies-used)  
- [Setup and Installation](#setup-and-installation)  
- [Usage](#usage)  
- [How It Works](#how-it-works)  
- [Example Output](#example-output)  
- [Contributing](#contributing)  
- [License](#license)  

## Introduction  
This project simulates an AI-driven Flappy Bird game where the agent learns to play using **NeuroEvolution of Augmenting Topologies (NEAT)**. The AI agent evolves over time, optimizing its survival strategy based on a fitness-based reward mechanism. The project utilizes **Python and Pygame** for visualization, making the decision-making process interpretable.  

## Features  
- **AI-Powered Gameplay**: Uses **NEAT** to train an autonomous Flappy Bird-playing agent.  
- **Evolutionary Learning**: The AI improves dynamically through genetic algorithms.  
- **Fitness-Based Rewards**: The model adapts and optimizes strategies based on survival performance.  
- **Hyperparameter Optimization**: Reduces training time and improves AI efficiency.  
- **Real-Time Visualization**: Uses **Pygame** to display the AI’s decision-making process.  
- **Modular & Efficient Codebase**: Optimized for readability and reduced execution time.  

## Technologies Used  
### Core Technologies  
- **Python**: Core programming language used.  
- **Pygame**: For game rendering and visualization.  
- **NEAT-Python**: For implementing the neuroevolution algorithm.  
- **Matplotlib** (optional): To visualize fitness evolution over generations.  

## Setup and Installation  
1. **Clone the repository** to your local machine:  
   ```bash
   git clone https://github.com/lishaangral/flappy-bird-using-NEAT.git
   ```
2. **Navigate to the project directory**:  
   ```bash
   cd flappy-bird-using-NEAT
   ```
3. **Install dependencies**:  
   ```bash
   pip install pygame neat-python matplotlib
   ```
4. **Run the simulation**:  
   ```bash
   python index.py
   ```

## Usage  
- **Run the script** and watch the AI-controlled birds learn to navigate through obstacles.  
- **Observe the fitness evolution**: The birds will gradually improve their survival strategies over multiple generations.  
- **Modify parameters** in the `config-feedforward.txt` file to adjust AI behavior.  

## How It Works  
### 1. **NeuroEvolution of Augmenting Topologies (NEAT)**  
The AI agent starts with a simple neural network and **evolves over time** by:  
- Mutating and optimizing the neural network architecture.  
- Adjusting weights and connections dynamically.  
- Selecting the fittest agents for the next generation.  

### 2. **Reinforcement Learning & Fitness Function**  
- The **fitness function** rewards the agent for surviving longer and passing more pipes.  
- Agents with higher scores are **more likely to pass their genes** to the next generation.  
- Over multiple generations, the AI **learns optimal movement patterns** to maximize survival.  

### 3. **Hyperparameter Optimization**  
- The neural network’s **learning rate, mutation rate, and topology growth** are tuned for efficiency.  
- The model learns to **avoid unnecessary movements** and **time jumps optimally**.  

## Example Output  
### Weak Initial AI (First Few Generations)  
- The birds struggle to navigate obstacles.  
- High mortality rate in early generations.  

### Optimized AI (After ~30 Generations)  
- Birds time their jumps accurately.  
- Survival rates significantly improve.  
- AI **outperforms human players** in some cases.  

## Contributing  
Contributions are welcome! If you'd like to improve the tool, optimize the AI, or add new features, feel free to fork the repository and submit a pull request.  

### Contribution Guidelines:  
- Follow best practices for **code modularity and efficiency**.  
- Ensure **backward compatibility** with existing configurations.  
- Test your changes thoroughly before submitting a **pull request**.  

## License  
This project is licensed under the **MIT License**. See the LICENSE file for more details.  

---
