---
layout: publication
title: 'How Much Do Contextualized Representations Encode Long-range Context?'
authors: Simeng Sun, Cheng-ping Hsieh
conference: "Arxiv"
year: 2024
bibkey: sun2024how
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.12292"}
tags: ['Transformer', 'GPT', 'Model Architecture', 'Training Techniques', 'Pretraining Methods']
---
We analyze contextual representations in neural autoregressive language
models, emphasizing long-range contexts that span several thousand tokens. Our
methodology employs a perturbation setup and the metric
*Anisotropy-Calibrated Cosine Similarity*, to capture the degree of
contextualization of long-range patterns from the perspective of representation
geometry. We begin the analysis with a case study on standard decoder-only
Transformers, demonstrating that similar perplexity can exhibit markedly
different downstream task performance, which can be explained by the difference
in contextualization of long-range content. Next, we extend the analysis to
other models, covering recent novel architectural designs and various training
configurations. The representation-level results illustrate a reduced capacity
for high-complexity (i.e., less compressible) sequences across architectures,
and that fully recurrent models rely heavily on local context, whereas hybrid
models more effectively encode the entire sequence structure. Finally,
preliminary analysis of model size and training configurations on the encoding
of long-range context suggest potential directions for improving existing
language models.
