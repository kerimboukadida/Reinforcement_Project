# Reinforcement_Project

we will be designing a custom environment that will involve flying a Chopper (or a helicopter) while avoiding obstacles mid-air.

Dependencies/Imports
We first begin with installing some important dependencies.

!pip install opencv-python 

!pip install pillow

!pip install gym

Description of the Environment
The environment that we are creating is basically a game that is heavily inspired by the Dino Run game, the one which you play in Google Chrome if you are disconnected from the Internet. There is a dinosaur, and you have to jump over cacti and avoid hitting birds. The distance you cover is representative of the reward you end up getting.

instead of a dinosaur, our agent is going to be a Chopper pilot.

The chopper has to cover as much distance as possible to get the maximum reward(MaxReward=2000). There will be birds that the chopper has to avoid.
The episode can also terminate if the Chopper runs out of fuel.
Just like birds, there are floating fuel tanks which the Chopper can collect to refuel the chopper to its full capacity (which is fixed at 1000 L), if the chopper collide with a bird we will subtract 100 from the reward.

The observation space can be either continuous or discrete. An example of a discrete action space is that of a grid-world where the observation space is defined by cells, and the agent could be inside one of those cells. An example of a continuous action space is one where the position of the agent is described by real-valued coordinates.
The action space can be either continuous or discrete as well. An example of a discrete space is one where each action corresponds to the particular behavior of the agent, but that behavior cannot be quantified.
