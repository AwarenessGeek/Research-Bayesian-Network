# Evaluating Evidence Quantity in Bayesian Network Inference

Overview
This project evaluates the impact of evidence quantity on the accuracy of learned probability distributions in Bayesian networks. It compares three structure learning algorithms - Hill Climb with BIC, Hill Climb with K2, and Tree-Augmented Naive Bayes (TAN) - across varying evidence levels.
Key Findings
   1. Critical evidence threshold of 45-60%: Additional evidence beyond this range significantly improved accuracy across algorithms.
   2. Network complexity impact: Higher complexity increased the need for more evidence to maintain prediction accuracy.
   3. Dataset size influence: Larger samples consistently reduced mean squared error in Bayesian network predictions.

Methodology
   1. Generated synthetic datasets from a 15-node ground truth Bayesian network.
   2. Systematically varied evidence availability from 0% to 100%.
   3. Calculated mean squared error (MSE) between predicted and true probability distributions.
   4. Conducted 100 stochastic experimental runs per configuration to account for variability.

Limitations and Future Work
   1. Synthetic data may not capture real-world complexities.
   2. Focused on specific algorithms; other methods could perform differently.
   3. Evaluate algorithms on diverse real-world datasets.
   4. Investigate methods for assessing evidence quality beyond just quantity.
