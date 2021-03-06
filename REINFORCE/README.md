
## REINFORCE
REINFORCE belongs to Policy Gradient methods, which directly parameterize the policy rather than a state value function.  
For more details about REINFORCE and other policy gradient algorithms, refer Chap 13 of  [Reinforcement Learning: An Introduction 2nd Edition](http://webdocs.cs.ualberta.ca/~sutton/book/the-book.html)  

Here we use REINFORCE Methods to solve game of Pong.  

## Pong  
The game of Pong is an Atari game which user control one of the paddle (the other one is control by a decent AI) and you have to bounce the ball past the other side. In reinforcement learning setting, the state is raw pixels and the action is moving the paddle UP or DOWN.  

<img src="https://github.com/borgwang/reinforce_py/raw/master/res/pong.png" width = "180" height = "256" alt="pong" align=center />   


## Requirements  
* Python 2.7  
* [Numpy](http://www.numpy.org/)   
* [Tensorflow](http://www.tensorflow.org)  
* [gym](https://gym.openai.com)  

## Run  
    python train_REINFORCE.py
