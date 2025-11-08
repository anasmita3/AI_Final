

Novelty in Architecture:

The hybrid model combines Convolutional Neural Networks (CNN), Attention mechanisms, and State Space Models (SSM) into a single pipeline, whereas MobileNetV2 primarily relies on deep convolutional layers with depthwise separable convolutions.

Attention modules in the hybrid model enable the network to focus dynamically on the most informative facial regions, improving feature discrimination beyond what fixed CNN filters can provide.

The integration of SSM allows the model to capture contextual and spatial dependencies across various parts of the face, something traditional CNNs and MobileNetV2 cannot explicitly achieve.

Performance Improvement:

The hybrid model achieves a much lower validation MAE for age prediction (6.81 vs. 11.33), showing its clear superiority in regression tasks that require capturing nuanced variations in age-related features.

Gender classification accuracy remains comparable (0.7787 vs. 0.7811), demonstrating that the hybrid adaptation does not compromise performance on categorical tasks while providing a substantial age estimation gain.

Interpretability and Flexibility:

Attention mechanisms contribute to model interpretability, as they highlight which regions the network considers most important for decision-making.

The hybrid approach is more flexible, as it can better adapt to different complexities in facial attributes by combining the strengths of local feature extractors (CNNs), saliency detection (attention), and sequential/context modeling (SSM).

Summary of Advantage:

By synergizing CNN, attention, and SSM modules, the hybrid model creates richer and more adaptive feature representations than MobileNetV2 alone.

This results in greater accuracy for age prediction on UTKFace, making the hybrid network especially suitable for challenging, multi-task facial analysis scenarios.

These improvements demonstrate that our hybrid model not only introduces architectural novelty but also delivers tangible benefits in predictive accuracy and robustness for facial attribute tasks.
