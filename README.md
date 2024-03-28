# Space Invaders - Atari (An OpenAI Gym Environment)
This repository contains a Python script for playing the classic arcade game Space Invaders using the Atari environment provided by OpenAI Gym. Additionally, it includes code for creating a deep learning model with Keras and building an agent using Keras-RL for training the model to play the game.

## Dependencies
- `tensorflow==2.13.0`
- `gym`
- `keras-rl2`
- `gym[atari]`
- `gym[accept-rom-license]`

This project was done using a venv rather than a conda, and also utilized the new venv as a ipykernel for easier execution !!!

# Instructions
Clone this repository to your local machine:
```
git clone https://github.com/yourusername/space-invaders.git

cd space-invaders
```

Install the dependencies using the provided requirements.txt file or the individual commands mentioned above.

Run the Python script space_invaders.py to start playing Space Invaders:


# Contents
SpaceInvaders_AtariGames.ipynb: The main Python script for playing Space Invaders.
README.md: The README file containing instructions for running the code.
requirements.txt: A text file listing the required Python packages.
# Usage
The script will play 5 games of Space Invaders using random actions.
It renders the game environment and prints the score for each episode.
A convolutional neural network (CNN) model is defined using Keras for learning to play Space Invaders.
The agent is built using Keras-RL, and a Deep Q-Network (DQN) agent is trained to play the game.
# Credits
This code is based on the OpenAI Gym Atari environment and Keras-RL library.
The Atari environment and Gym library are developed by OpenAI.
The Keras library is developed by the Keras team.

# The Game !!!

Space Invaders is a classic arcade game released in 1978 by Taito. It is one of the earliest shooting games and has had a significant impact on the video game industry. In the game, the player controls a spaceship that moves horizontally across the bottom of the screen and must shoot descending rows of aliens before they reach the bottom. The aliens also periodically fire projectiles at the player's spaceship, and the player must avoid being hit while eliminating as many aliens as possible. As the game progresses, the aliens move faster and the challenge increases, providing an addictive and challenging gaming experience.

# License
This project is licensed under the MIT License - see the LICENSE file for details.
