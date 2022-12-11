import numpy as np

# Define the number of trials and the probabilities of different scenarios
num_trials = 1000
prob_good = 0.6
prob_neutral = 0.3
prob_bad = 0.1

# Define the expected returns for each scenario
return_good = 1.2
return_neutral = 1.0
return_bad = 0.8

# Generate the scenarios using random numbers
scenarios = np.random.choice(["good", "neutral", "bad"], size=num_trials, p=[prob_good, prob_neutral, prob_bad])

# Calculate the returns for each scenario
returns = []
for scenario in scenarios:
    if scenario == "good":
        returns.append(return_good)
    elif scenario == "neutral":
        returns.append(return_neutral)
    else:
        returns.append(return_bad)

# Calculate the average return and standard deviation
avg_return = np.mean(returns)
std_dev = np.std(returns)

# Print the results
print("Average return: ", avg_return)
print("Standard deviation: ", std_dev)
