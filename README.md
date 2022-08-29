# Example SAC implementation with [ReLAx](https://github.com/nslyubaykin/relax)

This repository contains an [implementation](https://github.com/nslyubaykin/relax_sac_example/blob/master/sac_tutorial.ipynb) of soft actor critic (SAC) with ReLAx.

SAC actor was trained on Hopper-v2 Mujoco Gym environment for 1m env-steps. 

The graph of average return vs environment step is shown below (logs done every 10k steps):

![sac_training](https://github.com/nslyubaykin/relax_sac_example/blob/master/sac_training.png)

The distribution of estimated Q-values vs data Q-values is shown below:

![sac_q_func](https://github.com/nslyubaykin/relax_sac_example/blob/master/sac_q_func.png)

__Resulting Policy__:

https://user-images.githubusercontent.com/67604207/187180193-38bdc8aa-481d-4179-8550-2dbd28b015f0.mp4
