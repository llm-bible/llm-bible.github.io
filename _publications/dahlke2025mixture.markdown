---
layout: publication
title: 'Mixture Of Tunable Experts -- Behavior Modification Of Deepseek-r1 At Inference Time'
authors: Robert Dahlke, Henrik Klagges, Dan Zecha, Benjamin Merkel, Sven Rohr, Fabian Klemm
conference: "Arxiv"
year: 2025
bibkey: dahlke2025mixture
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.11096'}
tags: ['Interpretability and Explainability', 'Training Techniques', 'Model Architecture', 'Prompting', 'Interpretability', 'Pretraining Methods']
---
We present the Mixture-of-Tunable-Experts (MoTE), a method that extends the
Mixture-of-Experts architecture of Large Language Models (LLMs). Without
additional training, MoTE enables meaningful and focused behavior changes in
LLMs on-the-fly during inference time. By analyzing the digital LLM brain of
DeepSeek-R1 using a technique we dub 'functional Token Resonance Imaging'
(fTRI) -- inspired by fMRI and using prompts designed to elicit specific
behavior (e.g., 'What happened \{time\}\{place\}?') -- we empirically identify
distinctive experts associated with behaviors like refusal responses. Using
MoTE we are able to intervene and control such specific behavior. We switched
off the top 10 most refusal-relevant experts (0.07% of R1's 14,848 routed
experts), achieving a 52% refusal reduction on sensitive reference prompts
without performance degradation on MT-Bench. Random expert deactivation
resulted in smaller behavioral shifts with increased noise, whereas forced
expert activation led to significantly higher refusal rates. Our approach
shares similarities with sparse autoencoders (SAEs) in terms of explainability
and steerability. Unlike SAEs, MoTE does not require large training efforts, as
within MoEs with a vast number of experts, specialization already emerged
naturally during pretraining. Our findings suggest that significant functional
mechanisms in Mixture-of-Experts architectures can at least partially be
localized in a small number of specific experts, rather than being distributed
throughout the model's weights. Expert subgroups can be tuned to trigger
significant behavior variations, providing insights into the inner workings of
LLMs.
