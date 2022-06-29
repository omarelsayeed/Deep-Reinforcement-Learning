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

# The Algorithm 
- DQN replaces the traditional Q table by a network that takes the states and try to predict the Q values for every action.
- The update is minizing the Temporal Difference between Q(s,a,w) and r+max over all actions( Q(s'))
# Results 
- it took fairly long time to train but it converged after 45k steps and the agent then kept taking more rewards as it's balancing.
![download](https://user-images.githubusercontent.com/64399795/176384427-55226ddc-9820-4daa-b8d4-47b83298f22a.png)
https://user-images.githubusercontent.com/64399795/176076175-71899c1c-df9b-47ee-9533-f10392daf3ce.mp4


# References 
[Pybullet Documentation](https://docs.google.com/document/d/10sXEhzFRSnvFcl3XxNGhnD4N2SedqwdAvK3dsihxVUA/edit#)

[Pybullet Tutorial](https://www.youtube.com/watch?v=kZxPaGdoSJY&t=828s&ab_channel=DanielEid)

[Stanford Reinforcement Learning Lecture 1](https://www.youtube.com/watch?v=9g32v7bK3Co&t=3866s&ab_channel=StanfordOnline)

[Stanford Reinforcement Learning Lecture 2](https://www.youtube.com/watch?v=HpaHTfY52RQ&t=3989s&ab_channel=StanfordOnline)
