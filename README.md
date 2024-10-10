# Optimizers
Implementing deep learning optimizers manually provides a profound understanding of their mechanics. Here's an overview of key optimizers:

Gradient Descent (GD): Calculates gradients over the entire dataset to update parameters. While precise, it's computationally intensive for large datasets.

Stochastic Gradient Descent (SGD): Updates parameters using gradients from individual data points, offering faster iterations but introducing variability in updates.

Momentum: Enhances SGD by incorporating a fraction of the previous update, reducing oscillations and accelerating convergence.

RMSprop: Adapts learning rates by normalizing gradients with a running average of their magnitudes, leading to more stable updates.

Adam: Combines Momentum and RMSprop, utilizing both first and second moments of gradients to compute adaptive learning rates, often resulting in efficient convergence.

Manually coding these optimizers deepens your insight into model training dynamics.
