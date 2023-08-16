# Paper Title: CONTINUOUS CONTROL WITH DEEP REINFORCEMENT LEARNING
### Authors: Timothy P. Lillicrap ∗ , Jonathan J. Hunt ∗ , Alexander Pritzel, Nicolas Heess, Tom Erez, Yuval Tassa, David Silver & Daan Wierstra
Google DeepMind

## Abstract
- Extends DQN to the continuous action domain 
- Produces results competitive with planning algorithms with domain understanding 
- Trained end to end from pixels to actions 

## Introduction 

- Claim: DQN can only handle discrete and low dimensional action spaces. Note to self- let's test this out applying the DQN implemented on the lunar lander environment on a higher dimensional action space and see first hand what happens 
    - DQN cannot be straight forwardly applied to continuous action spaces due to the argmax function applied on action selection
    - One common approach to this problem is to discretize the problem but this has its own obvious drawbacks

- Proposition: Model-free, off-policy, actor-critic algorithm using deep function approximators 
    - Based on the deterministic policy gradient algorithm 
        - A naive approach to neural function approximation for this algorithm is unstable for challenging problems, this paper proposes leveraging breakthroughs from the DQN paper to deal with those issues (experience replay for off policy learning to reduce overfitting and a target v/s policy network) 
    - They call this Deep DPG (DDPG)
    