# Exploring-Upper-Confidence-Bound-UCB-Algorithm-for-Multi-Armed-Bandit-Problem
Upper Confidence Bound (UCB) Algorithm

This repository contains an implementation of the Upper Confidence Bound (UCB) algorithm for solving the multi-armed bandit problem. The UCB algorithm efficiently balances exploration and exploitation by selecting actions based on their estimated potential rewards while considering uncertainty.

Key Components:

Initialization: Initialize parameters such as the number of rounds (N) and the number of ads (d), along with empty arrays to track selections and rewards.

Main Loop: Iterate over each round (n) up to N.

Selection Phase: Calculate the upper confidence bound for each action based on its average reward and uncertainty.

Action Selection: Choose the action with the highest upper confidence bound for exploration or exploitation.

Updating Statistics: Update the selection count and total rewards for the chosen action.

Visualization: Plot a histogram to visualize the number of times each action was selected.
