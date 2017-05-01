# Deep Q Network

An implementation of q algorithm of Reinforcement Learning.

## Installation Dependencies:

1. Python 3
1. TensorFlow 1.0.1
1. pygame
1. gym

## How to Run?

```
git clone https://github.com/lufficc/dqn.git
cd dqn
python run.py
```

## Tricks for flappybird

Remove background image:
![remove-bg](https://github.com/lufficc/images/blob/master/dqn/remove-bg.png)

clip useless part:
![clip](https://github.com/lufficc/images/blob/master/dqn/clip.png)

resize and using binary image:
![bin](https://github.com/lufficc/images/blob/master/dqn/bin.png)

**decayed ε-greedy exploration, and when exploration, 0.95 probability to do nothing(because in flappy bird, most time wo do nothing). This is very important. It makes model converge in less than 2 hours.**