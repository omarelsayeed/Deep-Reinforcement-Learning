## Deep-Reinforcement-Learning

# Description
- This is my Implementation of the Deep Q network on a self balancing robot task.
- Using Keras , Pybullet , Numpy
for more information about the environment please see my previous project on [SelfBalancingRobot Q Learning](https://github.com/omarelsayeed/Self-Balancing-Robot-Pybullet-Simualtion).

# Usage 

- clone the repo 
- replace the bot file path to ur own machine's path.
- run everycell sequintially and tune the parameters for fun!
- You should have numpy , tensorflow , pybullet installed in order to run this project.

# DQN 
- DQN replaces the traditional Q table by a network that takes the states and try to predict the Q values for every action.
- The update is minizing the Temporal Difference between Q(s,a,w) and r+max over all actions( Q(s'))
# Results 
- it took fairly long time to train but it converged after 45k steps and the agent then kept taking more rewards as it's balancing.
![image](https://user-images.githubusercontent.com/64399795/176384945-ae01df87-0cde-4df3-beba-6ef3e2d46476.png)
![image](https://user-images.githubusercontent.com/64399795/176960764-e01f1b9f-1719-4918-a7f0-e4224d3cfc4c.png)

![My Robot](https://j.gifs.com/r2vgwL.gif)

# Double Deep Q Networks
Solving The Problem of maximization Bias in DQN

![image](https://user-images.githubusercontent.com/64399795/176984632-1e02f93e-a2a3-4739-bca7-d886b285e1a1.png)


# References 
[Pybullet Documentation](https://docs.google.com/document/d/10sXEhzFRSnvFcl3XxNGhnD4N2SedqwdAvK3dsihxVUA/edit#)

[Pybullet Tutorial](https://www.youtube.com/watch?v=kZxPaGdoSJY&t=828s&ab_channel=DanielEid)

[Stanford Reinforcement Learning Lecture 1](https://www.youtube.com/watch?v=9g32v7bK3Co&t=3866s&ab_channel=StanfordOnline)

[Stanford Reinforcement Learning Lecture 2](https://www.youtube.com/watch?v=HpaHTfY52RQ&t=3989s&ab_channel=StanfordOnline)
