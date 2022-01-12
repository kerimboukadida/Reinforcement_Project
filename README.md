# Reinforcement_Project

### Installation 
- !pip install gym 
- !pip install pyglet
- !pip3 install box2d-py
- !pip3 install gym[Box_2D]

### Contributors 
- Abdelkerim Boukadida 
- Achref Souibgui 

# Project : Car-Pole
<img src=cart_pole.gif width="400">

In this task we have to balance a rod on top of a cart. Number of action spaces is 2. Action space is discrete here.
- **`0`** - move cart to the left
- **`1`** - move cart to the right

**we used :**
- DQN for our q learning algorithm 
- MSE loss function
- Adam optimizer

# About
A pole is attached by an un-actuated joint to a cart, which moves along a frictionless track. The system is controlled by applying a force of 0 or 1 to the cart. The pendulum starts upright, and the goal is to prevent it from falling over.

