#Project 1: Navigation
Introduction
For this project, you will train an agent to navigate (and collect bananas!) in a large, square world.

Trained Agent

A reward of +1 is provided for collecting a yellow banana, and a reward of -1 is provided for collecting a blue banana. Thus, the goal of your agent is to collect as many yellow bananas as possible while avoiding blue bananas.

The state space has 37 dimensions and contains the agent's velocity, along with ray-based perception of objects around agent's forward direction. Given this information, the agent has to learn how to best select actions. Four discrete actions are available, corresponding to:

0 - move forward.
1 - move backward.
2 - turn left.
3 - turn right.
The task is episodic, and in order to solve the environment, your agent must get an average score of +13 over 100 consecutive episodes.

Getting Started
Download the environment from one of the links below. You need only select the environment that matches your operating system:

Linux: click here
Mac OSX: click here
Windows (32-bit): click here
Windows (64-bit): click here
(For Windows users) Check out this link if you need help with determining if your computer is running a 32-bit version or 64-bit version of the Windows operating system.

(For AWS) If you'd like to train the agent on AWS (and have not enabled a virtual screen), then please use this link to obtain the environment.

Place the file in the DRLND GitHub repository, in the p1_navigation/ folder, and unzip (or decompress) the file.

Instructions
Follow the instructions in Navigation.ipynb to get started with training your own agent!

(Optional) Challenge: Learning from Pixels
After you have successfully completed the project, if you're looking for an additional challenge, you have come to the right place! In the project, your agent learned from information such as its velocity, along with ray-based perception of objects around its forward direction. A more challenging task would be to learn directly from pixels!

To solve this harder task, you'll need to download a new Unity environment. This environment is almost identical to the project environment, where the only difference is that the state is an 84 x 84 RGB image, corresponding to the agent's first-person view. (Note: Udacity students should not submit a project with this new environment.)

You need only select the environment that matches your operating system:

Linux: click here
Mac OSX: click here
Windows (32-bit): click here
Windows (64-bit): click here
Then, place the file in the p1_navigation/ folder in the DRLND GitHub repository, and unzip (or decompress) the file. Next, open Navigation_Pixels.ipynb and follow the instructions to learn how to use the Python API to control the agent.

(For AWS) If you'd like to train the agent on AWS, you must follow the instructions to set up X Server, and then download the environment for the Linux operating system above.
