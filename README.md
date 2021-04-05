# drlnd_project1_navigation
Solution to the Banana environment for the assignment of the course 2 of Deep Reinforcement Learning nanodegree from Udacity.

## Project Details
This project is about the implementation of an agent that navigates in the **Banana** enevironment.   
The rules of the environment are very simple: the agent gets a reward of +1 everytime it collects a yellow banana 
and a reward of -1 everytime it collects a blue banana. Thus the aim of the agent is to collect as many yellow bananas 
as possible and avoid blue bananas.

There are 4 available actions:
- `0`: move forward
- `1`: move backward
- `2`: turn left
- `3`: turn right

The state space has 37 dimensions, including agent velocity and perception of the objects around the agent.

The environment is considered solved when the agent obtains a score greater or equal than +13, 
averaged over 100 consecutive episodes.

## Getting Started
In order to run the code that trains and evaluates the agent, you need to download and install the following repository:
```bash
git clone https://github.com/udacity/deep-reinforcement-learning.git
cd deep-reinforcement-learning/python
pip install .
```

This command will also install the needed dependencies in the environment (`torch`,  etc.). 

You also need to download the file containing the Banana environment at one of the following links, depending on your platform:
- Linux: [link](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux.zip)
- Mac OS: [link](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana.app.zip)
- Windows (32 bit): [link](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86.zip)
- Windows (64 bit): [link](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86_64.zip)

Once you have downloaded the `.zip` archive, you need to extract it and take note of the absolute location of the 
environment file.


## Instructions
The code to run the agent and the environment is in the notebook `Navigation.ipynb`, which you can open with `jupyter`:
```bash
jupyter notebook Navigation.ipynb
```
Before running any cell, make sure you substitute the value of the variable `ENVIRONMENT_FILE` 
to point to the file location in your computer.

You should be good to go for running the code in the notebook!