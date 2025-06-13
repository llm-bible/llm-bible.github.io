---
layout: publication
title: 'Adaptive Inference-time Compute: Llms Can Predict If They Can Do Better, Even Mid-generation'
authors: Rohin Manvi, Anikait Singh, Stefano Ermon
conference: "Arxiv"
year: 2024
bibkey: manvi2024adaptive
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.02725"}
tags: ['Model Architecture', 'Reinforcement Learning', 'RAG', 'GPT', 'Prompting']
---
Inference-time computation is a powerful paradigm to enhance the performance
of large language models (LLMs), with Best-of-N sampling being a widely used
technique. However, this method is computationally expensive, requiring both
(1) an external reward model and (2) the generation of multiple samples. In
this work, we introduce a new generative self-evaluation scheme designed to
adaptively reduce the number of generated samples while maintaining or even
improving performance. We use a generative reward model formulation, allowing
the LLM to predict mid-generation the probability that restarting the
generation will yield a better response. These predictions are obtained without
an external reward model and can be used to decide whether or not to generate
more samples, prune unpromising samples early on, or to pick the best sample.
This capability is very inexpensive as it involves generating a single
predefined token. Trained using a dataset constructed with real unfiltered
LMSYS user prompts, Llama 3.1 8B's win rate against GPT-4 on AlpacaEval
increases from 21% to 34% with 16 samples and math performance on GSM8K
improves from 84% to 91%. By sampling only when the LLM determines that it is
beneficial to do so and adaptively adjusting temperature annealing, we
demonstrate that 74% of the improvement from using 16 samples can be achieved
with only 1.2 samples on average. We further demonstrate that 50-75% of samples
can be pruned early in generation with minimal degradation in performance.
Overall, our methods enable more efficient and scalable compute utilization
during inference for LLMs.
