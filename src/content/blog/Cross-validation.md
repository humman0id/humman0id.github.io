#unit-1-classical-machine-learning 

# Questions

**1.**
You have only 100 labelled houses. If you set aside 20 for validation and 20 for test, that leaves 60 for training. Using the luck idea from [[Train, Validation and Test Splits, and Data Leakage]] note, what could go wrong with a validation score based on only 20 houses?

**ANSWER**

From the note, a model's performance with a validation set is partly skill and partly luck - a validation score based on only 20 houses would be more influenced by luck than that based on more houses, as there are less datapoints to cancel out the luck of the model. Therefore, each data point contributes a lot of noise to the validation score which can mislead the choice.

**2.**
You have 100 labelled houses and want to use all of them for both training and validating, but never validate on a house the model trained on.

**(i)** Invent a scheme that does that, and write it in plain steps.
**(ii)** For your scheme, how many models get trained, and which single number do you report?
**(iii)** What do you think is the cost of your scheme compared with a single validation set?

**ANSWER**