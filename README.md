# Weather_Recognition
**Executive Problem Statement:**

The task was to develop and evaluate deep learning models with different architectures to classify real images of five weather phenomena: fogsmag, rain, rime, sandstorm, and snow. The dataset consisted of 2,726 images from these five categories. The goal was to explore the dataset, develop and compare the performance of various models for weather phenomenon recognition, identify the class with the worst performance, and explain the reasons behind it. Additionally, potential approaches were to be discussed for improving the models' performance to make them suitable for real-world deployment, including strategies related to data collection, data processing, data formatting, and model architecture.

**Executive Solution Statement:**

- Data Preprocessing: Using a 70/30 split for training and testing sets with a fixed seed value of 42

- AI Model Development: Evaluating five weather phenomenon recognition predictive models, all using AdamW optimizer and keras L2 regularizer

- Report: Model 2 outperformed other architectures across all key metrics, including the highest accuracy (0.803178), Kappa score (0.753537), precision, recall, and F1-scores. Although the 'snow' class remained challenging, Model 2's minimal errors, a strong correlation between predictions and actuals, and robust generalization to unseen data-position it as the optimal solution for reliable real-world deployment in identifying weather conditions from images.
