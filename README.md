# Navigation_Udacity

This repository contains a solution for the Unity "Bananas" game. The object of the game is to collect as many yellow bananas as possible while avoiding blue bananas. The state space has 37 dimensions and contains the agent's velocity, along with ray-based perception of objects around the agent's forward direction. There are 4 possible actions, as given below:

    Move Forward
    Move Backward
    Turn Left
    Turn Right

The solution employs a Deep Q Network (DQN) in which a neural netwok is trained to return the best action (output) given an input state. The game is considered solved when the game playing "agent" is able to average a score of +13 over 100 consecutive episodes.

## Dependencies

Set up a python environment and download the Unity environment by following steps 1 and 2 of the instructions <a href="https://classroom.udacity.com/nanodegrees/nd893/parts/6b0c03a7-6667-4fcf-a9ed-dd41a2f76485/modules/4eeb16ab-5ac5-47bf-974d-12784e9730d7/lessons/69bd42c6-b70e-4866-9764-9bfa8c03cdea/concepts/319dc918-bd2c-4d3b-80a5-063bb5f1905a">here</a>.

# Installation

To run the DQN solution code, download the following files and place them in the directory with the Unity Banan Game folder:
    
    Navigation.ipynb
    dqn_agent.py
    model.py

The code can then be run by opening the Navigation notebook in the prescribed environment and running the cells.
