[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mahyaret/Navigation/blob/master/Navigation.ipynb)

# Navigation
DQN agent

<img src="img/banana-collector.gif" height="200">

### Introduction

For this project, an agent is trained to navigate and collect objects in a square world. A reward of +1 is provided for collecting a yellow object, and a reward of -1 is provided for collecting a blue object.  Thus, the goal of the agent is to collect as many yellow objects as possible while avoiding blue objects.  

The task is episodic, and the environment is considered to be solved, when the agent gets an average score of +13 over 100 consecutive episodes.

#### State-Action Represenation

- Observation space type: continuous
    - Observation space size (per agent): 37, corresponding to:
        - velocity of agent
        - ray-based perception of objects around agent's forward direction
- Action space type: discrete
    - Action space size (per agent): 4, corresponding to:
        - 0: move forward
        - 1: move backward
        - 2: turn left
        - 3: turn right

### Getting Started

1. conda create --name navigation python=3.6
2. conda activate navigation
3. conda install jupyter
4. pip install gym
   (make sure that pip is acting in your environment "type pip")
5. conda install pytorch=0.4.0 -c pytorch
6. cd C:\Users\YOUR_USERNAME\Documents\GitHub\Navigation\python
7. pip install .
8. install XQuartz from here: https://www.xquartz.org
   (remember to restart your mac)
9. Download the pre-compiled Unity Environment to "data" folder:
    - Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux.zip)
    - Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana.app.zip)
    - Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86.zip)
    - Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86_64.zip)
10. Follow the instructions in `Navigation.ipynb` to get started!
