---
layout: publication
title: 'Not All Tokens Are Created Equal: Perplexity Attention Weighted Networks For AI Generated Text Detection'
authors: Pablo Miralles-gonzález, Javier Huertas-tato, Alejandro Martín, David Camacho
conference: "Arxiv"
year: 2025
bibkey: mirallesgonzález2025not
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.03940"}
tags: ['Security', 'Training Techniques', 'Model Architecture', 'Tools', 'Reinforcement Learning', 'RAG', 'Pre-Training', 'Attention Mechanism']
---
The rapid advancement in large language models (LLMs) has significantly
enhanced their ability to generate coherent and contextually relevant text,
raising concerns about the misuse of AI-generated content and making it
critical to detect it. However, the task remains challenging, particularly in
unseen domains or with unfamiliar LLMs. Leveraging LLM next-token distribution
outputs offers a theoretically appealing approach for detection, as they
encapsulate insights from the models' extensive pre-training on diverse
corpora. Despite its promise, zero-shot methods that attempt to operationalize
these outputs have met with limited success. We hypothesize that one of the
problems is that they use the mean to aggregate next-token distribution metrics
across tokens, when some tokens are naturally easier or harder to predict and
should be weighted differently. Based on this idea, we propose the Perplexity
Attention Weighted Network (PAWN), which uses the last hidden states of the LLM
and positions to weight the sum of a series of features based on metrics from
the next-token distribution across the sequence length. Although not zero-shot,
our method allows us to cache the last hidden states and next-token
distribution metrics on disk, greatly reducing the training resource
requirements. PAWN shows competitive and even better performance
in-distribution than the strongest baselines (fine-tuned LMs) with a fraction
of their trainable parameters. Our model also generalizes better to unseen
domains and source models, with smaller variability in the decision boundary
across distribution shifts. It is also more robust to adversarial attacks, and
if the backbone has multilingual capabilities, it presents decent
generalization to languages not seen during supervised training, with LLaMA3-1B
reaching a mean macro-averaged F1 score of 81.46% in cross-validation with nine
languages.
