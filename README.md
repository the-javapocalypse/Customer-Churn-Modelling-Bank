# About Dataset

## Context
This is the dataset used in the section "ANN (Artificial Neural Networks)" of the Udemy course from Kirill Eremenko (Data Scientist & Forex Systems Expert) and Hadelin de Ponteves (Data Scientist), called Deep Learning A-Z™: Hands-On Artificial Neural Networks. The dataset is very useful for beginners of Machine Learning, and a simple playground where to compare several techniques/skills.

It can be freely downloaded here: https://www.superdatascience.com/deep-learning/

The story: A bank is investigating a very high rate of customer leaving the bank. Here is a 10.000 records dataset to investigate and predict which of the customers are more likely to leave the bank soon.

## Acknowledgements
Udemy instructors Kirill Eremenko (Data Scientist & Forex Systems Expert) and Hadelin de Ponteves (Data Scientist), and their efforts to provide this dataset to their students.

# Solution
This problem is solved by using an Artificial Nueral Network (ANN). The instructors of __Deep Learning A-Z™: Hands-On Artificial Neural Networks__ set the milestone for the accuracies as follows:
* 84% Accuracy = Bronze
* 85% Accuracy = Silver
* 86%+ Accuracy = Gold

I tired different topologies for the ANN (Deeper Topology vs Wider Topology. [Read More](https://machinelearningmastery.com/regression-tutorial-keras-deep-learning-library-python/)) with the combinations of different optimizers, dropouts etc. and found out that the deeper architecture with no dropout resulted in 86.7% Accuracy.
