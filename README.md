# Udacity-Deep Reinforcement Learning : -Collaboration-and-Competition



## Project Background:
Objective of the project is to train two agents to play tennis using Deep Deterministic Policy Gradients. The environment has 2 agents that control rackets to bounce balls over the net. If an agent hits the ball over the net, it receives a reward of +0.1. If an agent lets a ball hit the ground or hits the ball out of bounds, it receives a reward of -0.01. Thus, the goal of each agent is to keep the ball in play.


## Environment Setup
Follow the instructions below to explore the environment on your machine! You will also learn how to use the Python API to control your agent.

Follow the instructions [here](https://github.com/udacity/deep-reinforcement-learning/tree/master/p3_collab-compet) to set up the environment.



### Getting Started
1. Install Unity ML
https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Installation.md

2. Download the Unity ML environment from one of the links below based on your OS:
    - Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/Reacher_Linux.zip)
    - Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/Reacher.app.zip)
    - Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/Reacher_Windows_x86.zip)
    - Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/Reacher_Windows_x86_64.zip)

Then unzip the file and place the file in this project folder.

3. Create Conda Environment   

Install conda from conda.io. Create a new Conda environment with Python 3.6.

```bash
conda create --name deeprl python=3.6
source activate deeprl
```

4. Install Dependencies
```bash
cd python
pip install .
```


## How to run the agent
Follow the instructions in Tennis.ipynb to get started with training your agent!

agent.py contains code for the agent.

model.py contains the neural network code that is used by the agent.



## Results
The figure below show the performance and results of the model. The model performs well. The agent takes 490 episodes to achieve the goal.


<img src="images/result.png" width="70%" align="top-left" alt="" title="Results Graph" />

