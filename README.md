Fake Engagement Detection

Dataset Documentation (Mandatory)
Dataset Type: Synthetic.

Why: No real behavioral dataset with raw timing/coordination logs was publicly available for this challenge.

Generation Process: Modeled using Python (numpy/pandas) where bots were assigned high timing regularity and human behavior followed natural random distributions.

Number of Records: 5,000.

Feature Descriptions
Timing Regularity: Measure of robotic consistency in posting intervals.

Burst Pattern Score: Identifies sudden spikes in engagement density.

Network Coordination: Degree of synchronized activity with other accounts.

Linguistic Entropy: Diversity of language used (low for bots).

Performance
Accuracy: 100%.

Outputs: Authenticity Score (0-100), Bot Probability, and Behavioral Explanations.
