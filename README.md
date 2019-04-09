# Project : Collaboration and competition



![Trained Agent](https://user-images.githubusercontent.com/10624937/42135623-e770e354-7d12-11e8-998d-29fc74429ca2.gif)

### Details

The "collaboration and competition" project of the Udacity's Deep Reinforcement Learning Nanodegree consists in training two agents to control rackets to bounce a ball over a net. If an agent hits the ball over the net, it receives a reward of +0.1. If an agent lets a ball hit the ground or hits the ball out of bounds, it receives a reward of -0.01. Thus, the goal of each agent is to keep the ball in play.

The observation space is comprised of 8 variables corresponding to the position and velocity of the ball and racket. Each agent receives its own, local observation. Two continuous actions are available, corresponding to movement toward (or away from) the net, and jumping.

The task is episodic, and in order to solve the environment, your agents must get an average score of +0.5 (over 100 consecutive episodes, after taking the maximum over both agents). Specifically,

- After each episode, we add up the rewards that each agent received (without discounting), to get a score for each agent. This yields 2 (potentially different) scores. We then take the maximum of these 2 scores.
- This yields a single **score** for each episode.

In order for the environment to be solved, the episodes have to be repeated until getting an average score  of 0.5 (at least) over 100 consecutive episodes.



### Getting started

1. Clone the [DRLND Github repository](https://github.com/udacity/deep-reinforcement-learning) and follow the instructions in `README.md` to properly set up your python environment.
2. Download the Unity Environment from one of the links below, depending on your operating system:
   - Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis_Linux.zip) 
   - Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis.app.zip) 
   - Windows (32-bits): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis_Windows_x86.zip) 
   - Windows (64-bits): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis_Windows_x86_64.zip)
3. Unzip the file.



### Instructions

Open `Tennis.ipynb` to train the agent.