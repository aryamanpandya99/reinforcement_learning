# Actor Critic Methods 

Actor critic methods can be seen as the intersection of policy based methods and value based methods. In these algorithms, we update our policy explicitly just like we would in Policy Gradient methods. However, we use a value function (which we also update and keep track of) in order to estimate the performance (loss) of the policy function. 

In this sense our actor is our policy being optimized and our critic is our q-function which criticizes the policy being generated. This subdirectory contains a collection of different algorithms that belong to this family. 

The first of these implemented here is Deep Deterministic Policy Gradients (DDPG) which combines ideas from DQN and Deterministic Policy Gradients (DPG). 
