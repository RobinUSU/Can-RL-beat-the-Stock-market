# Reinforcement Learning Stock trading

#A methological Study of RL Stock market Trading programs

The programs take in stock data as input, with three options. Buy, Sell, or hold.
The aim was to maximize the maximum return over a series of time and compare the gains and training times in a methodological study between the algorithms using Tensorflow and PPO, A2C, DIJA, Ensemble methods.
 
# First Baseline implementation

I  wanted to compare a variety of approaches between algorithms to measure the differences of gains and the best performing algorithm.
The first model trained during a year when stock dropped in value, simply learned how to avoid losing value instead of gaining it. 
The following on the left was the first baseline Implementation implemented, A DQN (Deep Q Network) agent.

<img src=graphs/Method[1]-Results.JPG width="500">

(Baseline Source: https://github.com/Albert-Z-Guo/Deep-Reinforcement-Stock-Trading ) 

# Second Baseline Implementation

Supported Algorithms: PPO, Ensemble, A2C, DIJA methods 
Training is done in 63, 1 week long epochs where the program is allowed to buy and sell.
Verification is then done in another set of 63 weekly epochs to evaluate data.
The final Verification process then evaluates the stocks over 4 years to verify itself.

(Baseline Source: https://github.com/AI4Finance-Foundation/Deep-Reinforcement-Learning-for-Automated-Stock-Trading-Ensemble-Strategy-ICAIF-2020 ) 

