## Reinforcement Learning Final Project

>Email: liu1405214289@163.com

### Background
This project is reproduced in the paper "Continuous control with deep reinforcement learning"

You can view this paper through the link below

http://arxiv.org/abs/1509.02971

### Introduction

- In this project, I first reproduced the original DDPG algorithm based on OpenAI Gym and Pytorch, and applied the algorithm to test in multiple continuous action space environments. You can see the `RL_ddpg.py`

- According to the test results of a large number of experiments, I analyzed the sensitive items and weaknesses of the original version of the DDPG algorithm

- For different sensitive items, I propose improvements in three different directions for DDPG
  -   Optimized action selection and random start: You can see the `RL_ddpg_action.py`
  -   Simulated Annealing Update Hyperparameters: You can see the `RL_ddpg_lr.py`
  -   Rebuild the network structure: You can see the `RL_ddpg_network.py`

### How to run

```
git clone https://github.com/VAthree/RL_ddpg.git
cd RL_ddpg
python RL_ddpg.py
```
If you want to change the test environment of the continuous action space, you can change the settings of the gym parameters

### Result

<img width="784" alt="72313abf7954f118abeafba38a26837" src="https://user-images.githubusercontent.com/56064364/150277589-612aaa11-8e91-4fd2-9ed9-cc870e823c79.png">

