# Project Report

### Algorithm

Vanilla Deep Q Learning with fully connected deep neural network.

DNN Layers:

* **input layer**: 37 nodes (environment state size)
* **hidden layer**: 64 nodes, ReLU
* **hidden layer**: 64 nodes, ReLU
* **output layer**: 4 nodes (number of available actions)

Hyperparameters:

* **replay buffer size**: 10,000
* **batch size**: 64
* **learning rate**: 0.0005
* **discount**: 0.99
* **epsilon**: start=1.0, end=0.01, decay=0.995
* **number of episodes**: 2000

### Training

![Training](img/training.png)

```
Episode 100     Average Score: 0.78
Episode 200     Average Score: 3.56
Episode 300     Average Score: 6.97
Episode 400     Average Score: 9.60
Episode 500     Average Score: 12.70
Episode 600     Average Score: 14.40
Episode 700     Average Score: 15.20
Episode 800     Average Score: 15.14
Episode 900     Average Score: 14.60
Episode 1000    Average Score: 14.66
Episode 1100    Average Score: 14.54
Episode 1200    Average Score: 15.07
Episode 1300    Average Score: 15.36
Episode 1400    Average Score: 15.98
Episode 1500    Average Score: 15.54
Episode 1600    Average Score: 15.28
Episode 1700    Average Score: 15.06
Episode 1800    Average Score: 15.86
Episode 1900    Average Score: 14.53
Episode 2000    Average Score: 15.69
```

### Results

Random agent

![Random agent](img/random_agent.gif)

Dumb agent (before training)

![Dumb agent](img/dumb_agent.gif)

Smart agent (after training)

![Smart agent](img/smart_agent.gif)

Average score for 100 episodes: 16.53

### Future ideas

1. Learn from pixels
2. Double DQN
3. Prioritized Experience Replay
4. Dueling Deep Q Networks
5. Rainbow
