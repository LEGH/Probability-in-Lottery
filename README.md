# Probability in Lottery

Probability and Combinatorics principles can help us to understand better the logic behind lottery. This will help us, without any doubt, to think more carefully in our decisions when we are in the presence of randomness.

## Goal of the project
The goal in this projet is to give some awareness about probabilistic phenomena. Specially, it's aimed to people that are really obsessed in these kind of games or strongly believe in some lucky, magical strategies. This is an invitation to discover maths behind this game. 

## Getting started
This notebook is coded in Python 3. It only requires pandas library.
We use free available and real data from 6/49 lottery in Canada. This dataset can be found in Kaggle: https://www.kaggle.com/datascienceai/lottery-dataset

## Mathematical concepts
There some concepts that we use constantly throughout the notebook:
- Factorial n!:  Product of all positive integers less than or equal to n
- Combination C(n,k): Number of ways we can combine things, when the order does not matter.
- Probability P(A): Number between 0 and 1 that tell us how likely an event is to occur. In this notebook, we assume two things: independance and equiprobability. So, our definition of probability can be interpreted as a ration between counting objects:  favorable outcomes / total outcomes.

## Road map
To accomplish our goal, the following steps are done:
- **Context:** Explain quickly about dataset and the problem. 
- **Basic concepts:** Useful maths formules and functions. 
- **Win the big prize:** Calculate the probability to win the big prize.
- **Compare to past editions:** Verify if a given set of numbers would has won in the past.
- **Small prizes:** See the behaviour of the probability when we change a parameter (number of exact numbers)
