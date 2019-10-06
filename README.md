# Reinforcement Learning: An Introduction
C++ replication for Sutton & Barto's book [*Reinforcement Learning: An Introduction (2nd Edition)*](http://incompleteideas.net/book/the-book-2nd.html)

Inspired by [https://github.com/ShangtongZhang/reinforcement-learning-an-introduction](https://github.com/ShangtongZhang/reinforcement-learning-an-introduction)

# Code at [math21/src/rl](https://github.com/LilyBeauty/math21/tree/master/src/rl)

# Contents 

### Chapter 1
1. Tic-Tac-Toe

### Chapter 2
1. Figure 2.1: An exemplary bandit problem from the 10-armed testbed
2. Figure 2.2: Average performance of epsilon-greedy action-value methods on the 10-armed testbed 
    * [average reward](https://raw.githubusercontent.com/LilyBeauty/reinforcement-learning-an-introduction/master/images/figure_2_2/average_reward.png)
    * [optimal action](https://raw.githubusercontent.com/LilyBeauty/reinforcement-learning-an-introduction/master/images/figure_2_2/optimal_action.png)
3. Figure 2.3: Optimistic initial action-value estimates
    * [optimal action](https://raw.githubusercontent.com/LilyBeauty/reinforcement-learning-an-introduction/master/images/figure_2_3/optimal_action.png)
4. Figure 2.4: Average performance of UCB action selection on the 10-armed testbed
    * [average reward](https://raw.githubusercontent.com/LilyBeauty/reinforcement-learning-an-introduction/master/images/figure_2_4/average_reward.png)
5. Figure 2.5: Average performance of the gradient bandit algorithm
   * [optimal action](https://raw.githubusercontent.com/LilyBeauty/reinforcement-learning-an-introduction/master/images/figure_2_5/optimal_action.png)
6. Figure 2.6: A parameter study of the various bandit algorithms
   * [average reward](https://raw.githubusercontent.com/LilyBeauty/reinforcement-learning-an-introduction/master/images/figure_2_6/average_reward.png)

### Chapter 3
1. [Figure 3.2: Grid example with random policy](https://raw.githubusercontent.com/LilyBeauty/reinforcement-learning-an-introduction/master/images/figure_3_2/log.txt)
2. [Figure 3.5: Optimal solutions to the gridworld example](https://raw.githubusercontent.com/LilyBeauty/reinforcement-learning-an-introduction/master/images/figure_3_5/log.txt)

### Chapter 4
1. [Figure 4.1: Convergence of iterative policy evaluation on a small gridworld](https://raw.githubusercontent.com/LilyBeauty/reinforcement-learning-an-introduction/master/images/figure_4_1/log.txt)
2. Figure 4.2: Jack’s car rental problem
    * [optimal value](https://raw.githubusercontent.com/LilyBeauty/reinforcement-learning-an-introduction/master/images/figure_4_2/optimal_value.png)
    * [optimal policy](https://raw.githubusercontent.com/LilyBeauty/reinforcement-learning-an-introduction/master/images/figure_4_2/optimal_policy.png)
3. Figure 4.2 (synchronous): Jack’s car rental problem
    * [optimal value](https://raw.githubusercontent.com/LilyBeauty/reinforcement-learning-an-introduction/master/images/figure_4_2_synchronous/optimal_value.png)
    * [optimal policy](https://raw.githubusercontent.com/LilyBeauty/reinforcement-learning-an-introduction/master/images/figure_4_2_synchronous/optimal_policy.png)
4. Figure 4.3: The solution to the gambler’s problem
   * [value estimations](https://raw.githubusercontent.com/LilyBeauty/reinforcement-learning-an-introduction/master/images/figure_4_3/value_estimations.png)
   * [final policy](https://raw.githubusercontent.com/LilyBeauty/reinforcement-learning-an-introduction/master/images/figure_4_3/final_policy.png)

### Chapter 5
1. [Figure 5.1: Approximate state-value functions for the blackjack policy](https://raw.githubusercontent.com/LilyBeauty/reinforcement-learning-an-introduction/master/images/figure_5_1/log.txt)
2. [Figure 5.2: The optimal policy and state-value function for blackjack found by Monte Carlo ES](https://raw.githubusercontent.com/LilyBeauty/reinforcement-learning-an-introduction/master/images/figure_5_2/log.txt)
3. [Figure 5.3: Weighted importance sampling](https://raw.githubusercontent.com/LilyBeauty/reinforcement-learning-an-introduction/master/images/figure_5_3/Ordinary_and_Weighted_Importance_Sampling.png)

### Chapter 6
1. Example 6.2: Random walk
    * [compute state value](https://raw.githubusercontent.com/LilyBeauty/reinforcement-learning-an-introduction/master/images/figure_6_2_left/estimated_value.png)
    * [rms error](https://raw.githubusercontent.com/LilyBeauty/reinforcement-learning-an-introduction/master/images/figure_6_2_right/RMS.png)
2. [Figure 6.3: Batch updating](https://raw.githubusercontent.com/LilyBeauty/reinforcement-learning-an-introduction/master/images/figure_6_3/batch_updating.png)
3. Figure 6.4: The cliff-walking task
    * [sum reward](https://raw.githubusercontent.com/LilyBeauty/reinforcement-learning-an-introduction/master/images/figure_6_4/sum_r.png)
    * [optimal policy](https://raw.githubusercontent.com/LilyBeauty/reinforcement-learning-an-introduction/master/images/figure_6_4/optimal_policy.txt)
4. [Figure 6.6: Interim and asymptotic performance of TD control methods](https://raw.githubusercontent.com/LilyBeauty/reinforcement-learning-an-introduction/master/images/figure_6_6/sum_reward_per_episode.png)

# Environment
* math21

# Usage
> All files are self-contained
```commandline
git clone https://github.com/LilyBeauty/math21.git
cd math21
mkdir build
cd build
cmake ..
make && make install
```

