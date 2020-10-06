# Deep RL Bootscamp (Berkeley CA)

Link to course: [https://sites.google.com/view/deep-rl-bootcamp/home](https://sites.google.com/view/deep-rl-bootcamp/home)

## Lab 03

This Repo contains the lab 03: [https://sites.google.com/view/deep-rl-bootcamp/labs](https://sites.google.com/view/deep-rl-bootcamp/labs)

#### Hyperparameters
In the following, the influence of the hyperparameters is examined. The goal is not to achieve good performance but to understand the different parameters.

**Baseline: Performance on Pong:**

Average Return:
![Average Return Baseline](./plots/base/average_return.png)

Average Discounted Return:
![Average Discounted Return Baseline](./plots/base/average_discounted_return.png)

Average Error:
![Average Error Baseline](./plots/base/average_error.png)

**Increasing the Discount Factor gamma** (increased from 0.99 to 0.995)
Average Return:
![Average Return Increased Discount](./plots/discount_0-995/average_return.png)

Average Discounted Return:
![Average Discounted Return Increased Discount](./plots/discount_0-995/average_discounted_return.png)

Average Error:
![Average Error Increased Discount](./plots/discount_0-995/average_error.png)

**Decreasing the Discount Factor gamma** (decreased from 0.99 to 0.985)

Average Return:
![Average Return Decreased Discount](./plots/discount_0-985/average_return.png)

Average Discounted Return:
![Average Discounted Return Decreased Discount](./plots/discount_0-985/average_discounted_return.png)

Average Error:
![Average Error Decreased Discount](./plots/discount_0-985/average_error.png)

**Increasing the Fraction of Expl. Parameter epsilon** (increased from 0.1 to 0.2)

Average Return:
![Average Return Increased Epsilon](./plots/eps_0-2/average_reward.png)

Average Discounted Return:
![Average Discounted Return Increased Epsilon](./plots/eps_0-2/average_discounted_reward.png)

Average Error:
![Average Error Increased Epsilon](./plots/eps_0-2/average_error.png)

**Decreasing the Fraction of Expl. Parameter epsilon** (decreased from 0.1 to 0.05)

Average Return:
![Average Return Decreased Epsilon](./plots/eps_0-05/average_return.png)

Average Discounted Return:
![Average Discounted Return Decreased Epsilon](./plots/eps_0-05/average_discounted_return.png)

Average Error:
![Average Error Decreased Epsilon](./plots/eps_0-05/average_error.png)



## Other labs
- [https://github.com/sagerpascal/deep-rl-bootcamp-lab01](https://github.com/sagerpascal/deep-rl-bootcamp-lab01)
- [https://github.com/sagerpascal/deep-rl-bootcamp-lab2](https://github.com/sagerpascal/deep-rl-bootcamp-lab2)
- [https://github.com/sagerpascal/deep-rl-bootcamp-lab4](https://github.com/sagerpascal/deep-rl-bootcamp-lab2)
