---
layout: publication
title: 'Benford''s Curse: Tracing Digit Bias To Numerical Hallucination In Llms'
authors: Jiandong Shao, Yao Lu, Jianfei Yang
conference: "Arxiv"
year: 2025
bibkey: shao2025tracing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2506.01734"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Pruning', 'Ethics and Bias', 'Pretraining Methods']
---
Large Language Models (LLMs) exhibit impressive performance on complex reasoning tasks, yet they frequently fail on basic numerical problems, producing incorrect outputs. Inspired by Benford's Law -- a statistical pattern where lower digits occur more frequently as leading digits -- we hypothesize that the long-tailed digit distributions in web-collected corpora may be learned by LLMs during pretraining, leading to biased numerical generation. To investigate the hypothesis, we first examine whether digits frequencies in pretraining corpus (OLMo2) follows Benford's law. We then construct an evaluation benchmark with uniformly distributed ground-truth digits across seven numerical reasoning tasks. Our evaluation results demonstrate that leading open-source LLMs show a consistent pattern of digit bias that resembles Benford's law. Through logit-lens tracing and neuron-level dissection, we identify that this bias arises predominantly from a small subset of highly digit-selective feed-forward network (FFN) neurons in the deeper layers. Finally, we demonstrate that pruning these neurons mitigates imbalanced overgeneration and partially corrects erroneous outputs, providing causal evidence that fine-grained pretraining digit bias can propagate into model behavior. Our findings reveal a fundamental connection between corpus-level statistics and symbolic failure modes in LLMs, offering a new lens for diagnosing and mitigating hallucinations in numerical tasks.
