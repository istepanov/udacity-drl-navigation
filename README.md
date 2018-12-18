# Project 1: Navigation

_Udacity Deep Reinforcement Learning Nanodegree_

![Smart agent](img/smart_agent.gif)

### Project details

Train an agent to navigate and collect bananas in a large, square world.

A reward of +1 is provided for collecting a yellow banana, and a reward of -1 is provided for collecting a blue banana. The goal is to collect as many yellow bananas as possible while avoiding blue bananas.

The state space has 37 dimensions and contains the agent's velocity, along with ray-based perception of objects around the agent's forward direction.

Four discrete actions are available, corresponding to:

* `0` - move forward
* `1` - move backward
* `2` - turn left
* `3` - turn right

The task is episodic, and in order to solve the environment, the agent must get an average score of +13 over 100 consecutive episodes.

### Prerequisites

* [Miniconda](https://conda.io/miniconda.html)

### Dependencies

To set up your python environment to run the code in this repository, follow the instructions below.

    conda create --name drlnd python=3.6
    source activate drlnd
    git clone https://github.com/udacity/deep-reinforcement-learning.git
    cd deep-reinforcement-learning/python
    pip install .

### How to Run

Clone this repo, then run `jupyter notebook` to access the notebook.

### Notebook

[Link](Navigation.ipynb)

### Report

[Link](report.md)
