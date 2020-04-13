# Collect Bananas
### Introduction
In this project, a [unity machine learning agent](https://github.com/Unity-Technologies/ml-agents) is trained using deep reinforcement learning to collect yellow bananas in a world with yellow and blue bananas. If the agent succeeds in collecting a banana, it is given a reward of +1. If a blue banana is collected, the agent gets a reward of -1.

![Banana Collector Environment](https://github.com/Johannathorsen/collect-bananas/blob/master/Media/trained_collector.gif)

The state space has 37 dimensions and consists of the agent's velocity together with information about objects in front of the agent. The agent is able to choose between four different actions:

 - ```0``` - move forward
 - ```1``` - move backward
 - ```2``` - turn left
 - ```3``` - turn right

### Goal
The agent trained until it succeeds in getting a cumulative reward of +13 in average over 100 consecutive episodes, where one episode consists of 300 steps.

### Getting Started
Prepare an anaconda environment using [these instructions](https://github.com/udacity/deep-reinforcement-learning#dependencies) and open up the file collect-bananas.ipynb in jupyter notebook.