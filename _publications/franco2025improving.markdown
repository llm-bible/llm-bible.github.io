---
layout: publication
title: 'Improving Quantization With Post-training Model Expansion'
authors: Giuseppe Franco, Pablo Monteagudo-lago, Ian Colbert, Nicholas Fraser, Michaela Blott
conference: "Arxiv"
year: 2025
bibkey: franco2025improving
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.17513"}
tags: ['Efficiency and Optimization', 'RAG', 'Pruning', 'Training Techniques', 'Quantization']
---
The size of a model has been a strong predictor of its quality, as well as
its cost. As such, the trade-off between model cost and quality has been
well-studied. Post-training optimizations like quantization and pruning have
typically focused on reducing the overall volume of pre-trained models to
reduce inference costs while maintaining model quality. However, recent
advancements have introduced optimization techniques that, interestingly,
expand models post-training, increasing model size to improve quality when
reducing volume. For instance, to enable 4-bit weight and activation
quantization, incoherence processing often necessitates inserting online
Hadamard rotations in the compute graph, and preserving highly sensitive
weights often calls for additional higher precision computations. However, if
application requirements cannot be met, the prevailing solution is to relax
quantization constraints. In contrast, we demonstrate post-training model
expansion is a viable strategy to improve model quality within a quantization
co-design space, and provide theoretical justification. We show it is possible
to progressively and selectively expand the size of a pre-trained large
language model (LLM) to improve model quality without end-to-end retraining. In
particular, when quantizing the weights and activations to 4 bits for Llama3
1B, we reduce the zero-shot accuracy gap to full precision by an average of 3%
relative to both QuaRot and SpinQuant with only 5% more parameters, which is
still a 3.8% reduction in volume relative to a BF16 reference model.
