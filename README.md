# Evaluating Evidence Quantity in Bayesian Network Inference

Overview
This project evaluates the impact of evidence quantity on the accuracy of learned probability distributions in Bayesian networks. It compares three structure learning algorithms - Hill Climb with BIC, Hill Climb with K2, and Tree-Augmented Naive Bayes (TAN) - across varying evidence levels.
Key Findings

Critical evidence threshold of 45-60%: Additional evidence beyond this range significantly improved accuracy across algorithms.
Network complexity impact: Higher complexity increased the need for more evidence to maintain prediction accuracy.
Dataset size influence: Larger samples consistently reduced mean squared error in Bayesian network predictions.

Methodology

Generated synthetic datasets from a 15-node ground truth Bayesian network.
Systematically varied evidence availability from 0% to 100%.
Calculated mean squared error (MSE) between predicted and true probability distributions.
Conducted 100 stochastic experimental runs per configuration to account for variability.

Limitations and Future Work

Synthetic data may not capture real-world complexities.
Focused on specific algorithms; other methods could perform differently.
Evaluate algorithms on diverse real-world datasets.
Investigate methods for assessing evidence quality beyond just quantity.
