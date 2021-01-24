# deep_learning
The agents were trained based on the provided dqn exercises and achieved an average score of 13 or higher.
# Enviroment
Environment:
State: 37 discrete spaces[37].
Action: Move forward, move backward, turn right, turn left [4].
Reward: 1. +1 if you get a yellow banana, -1 if you get a blue banana
# Solutions
Using the Bellman operator, we obtain an action value function from historical data.
The approximation function of the action value function is a neural network.
The input is the state and the output is the action.
The value is obtained by reducing the error between the approximation function and the target function.
Double DQN is not applied.
