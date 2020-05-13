﻿
# RL Banana Navigation Project

In this project I used Deep Reinforement Learning metheods in order to train an agent in the [Reacher](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Learning-Environment-Examples.md#reacher) environment ,  where a double-jointed arm can move to target locations.

[![Trained Agent](https://user-images.githubusercontent.com/10624937/43851024-320ba930-9aff-11e8-8493-ee547c6af349.gif "Trained Agent")](https://user-images.githubusercontent.com/10624937/43851024-320ba930-9aff-11e8-8493-ee547c6af349.gif)
A reward of +0.1 is provided for each step that the agent's hand is in the goal location. Thus, the goal of your agent is to maintain its position at the target location for as many time steps as possible.

The observation space consists of 33 variables corresponding to position, rotation, velocity, and angular velocities of the arm. Each action is a vector with four numbers, corresponding to torque applicable to two joints. Every entry in the action vector should be a number between -1 and 1.


# Project goal

The goal of this project is to train an agent to acheive an average score of 30+ over 100 consecutive episodes, in least amount of epochs.


### Getting Started

1.  Download the environment from one of the links below. You need only select the environment that matches your operating system:
    
    -   **_Version 1: One (1) Agent_**
        
        -   Linux:  [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher_Linux.zip)
        -   Mac OSX:  [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher.app.zip)
        -   Windows (32-bit):  [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher_Windows_x86.zip)
        -   Windows (64-bit):  [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher_Windows_x86_64.zip)
    -   **_Version 2: Twenty (20) Agents_**
        
        -   Linux:  [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/Reacher_Linux.zip)
        -   Mac OSX:  [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/Reacher.app.zip)
        -   Windows (32-bit):  [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/Reacher_Windows_x86.zip)
        -   Windows (64-bit):  [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/Reacher_Windows_x86_64.zip)
    
    (_For Windows users_) Check out  [this link](https://support.microsoft.com/en-us/help/827218/how-to-determine-whether-a-computer-is-running-a-32-bit-version-or-64)  if you need help with determining if your computer is running a 32-bit version or 64-bit version of the Windows operating system.
    
    (_For AWS_) If you'd like to train the agent on AWS (and have not  [enabled a virtual screen](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Training-on-Amazon-Web-Service.md)), then please use  [this link](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher_Linux_NoVis.zip)  (version 1) or  [this link](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/Reacher_Linux_NoVis.zip)  (version 2) to obtain the "headless" version of the environment. You will  **not**  be able to watch the agent without enabling a virtual screen, but you will be able to train the agent. (_To watch the agent, you should follow the instructions to  [enable a virtual screen](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Training-on-Amazon-Web-Service.md), and then download the environment for the  **Linux**  operating system above._)
    
2.  Place the file in the DRLND GitHub repository, in the  `p2_continuous-control/`  folder, and unzip (or decompress) the file.
    

## Install

This project requires  **Python 3.x**  and the following Python libraries installed:

-   [NumPy](http://www.numpy.org/)
-   [matplotlib](http://matplotlib.org/)
-   [pytorch](https://pytorch.org/)

You will also need to have software installed to run and execute an  [iPython Notebook](http://ipython.org/notebook.html)

We recommend to install  [Anaconda](https://www.continuum.io/downloads), a pre-packaged Python distribution that contains all of the necessary libraries and software for this project.

## Run

In a terminal or command window, navigate to the top-level project directory ` (that contains this README) and run one of the following commands:

ipython notebook Continuous_Control.ipynb

or

jupyter notebook Continuous_Control.ipynb

This will open the iPython Notebook software and project file in your browser.
