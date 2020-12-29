### 1. Project Details about Environment
This project focuses on training an agent that navigates across a square game board, where yellow and blue bananas are scattered. The task is to collect as many yellow bananas as possible and avoid collecting blue bananas. Thus, for each time when a yellow banana is collected the agent will be given with +1 reward, but with -1 reward if a blue banana is collected. The agent is allowed to take four discrete actions (find the keys on your keyboard) when the state is continuous:
- `0` - move forward
- `1` - move backward
- `2` - turn left
- `3` - turn right
### 2. When the environment is considered solved
Banana collection is an episodic game. To solve this task, the agent is required to secure an average score of at least +13 points over 100 consecutive episodes.
### 3. How to get start
- Gain a basic understanding of [Unity Environment](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Learning-Environment-Examples.md#banana-collector)
- Set up a Python 3.6 Environment to install [Dependencies](https://github.com/udacity/deep-reinforcement-learning#dependencies) involving PyTorch, the ML-Agent toolkit and a few more Python packages.
- Download a Unity Environment for [Windows(64-bit)](https://classroom.udacity.com/nanodegrees/nd893/parts/6b0c03a7-6667-4fcf-a9ed-dd41a2f76485/modules/e7499d4f-24f9-42ec-9864-23adcfa4e241/lessons/69bd42c6-b70e-4866-9764-9bfa8c03cdea/concepts/319dc918-bd2c-4d3b-80a5-063bb5f1905a)/[Windows(32-bit)](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86.zip)/[Mac OSX](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana.app.zip)/[LINUX](https://classroom.udacity.com/nanodegrees/nd893/parts/6b0c03a7-6667-4fcf-a9ed-dd41a2f76485/modules/e7499d4f-24f9-42ec-9864-23adcfa4e241/lessons/69bd42c6-b70e-4866-9764-9bfa8c03cdea/concepts/319dc918-bd2c-4d3b-80a5-063bb5f1905a)
- Follow instructions on how to enable a [Virtual Screen](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Training-on-Amazon-Web-Service.md)
### 4. Instructions
- Run [Navigation.ipynb](/Navigation.ipynb)
- See an [untrained version](https://youtu.be/tCtFOyoverk) and my trained agent collecting bananas on YouTube ([link](https://www.youtube.com/watch?v=YRjJCcCDLC8)). You are mostly welcome to leave comments below :peach:
