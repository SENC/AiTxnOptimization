# AiTxnOptimization
***Optimal Executing of Portfolio Txns***

Part of Udacity Deep Reinforcement Learning Nano Degree.

There are several types of RL algorithms, and they can be divided into three groups:

**Critic-Only**: Critic-Only methods, also known as Value-Based methods, first find the optimal value function and then derive an optimal policy from it.

**Actor-Only**: Actor-Only methods, also known as Policy-Based methods, search directly for the optimal policy in policy space. This is typically done by using a parameterized family of policies over which optimization procedures can be used directly.

**Actor-Critic**: Actor-Critic methods combine the advantages of actor-only and critic-only methods. In this method, the critic learns the value function and uses it to determine how the actor's policy parramerters should be changed. In this case, the actor brings the advantage of computing continuous actions without the need for optimization procedures on a value function, while the critic supplies the actor with knowledge of the performance. Actor-critic methods usually have good convergence properties, in contrast to critic-only methods. 

**The Deep Deterministic Policy Gradients (DDPG) algorithm** is one example of an actor-critic method.
