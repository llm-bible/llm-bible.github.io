---
layout: publication
title: Interpreting Learned Feedback Patterns In Large Language Models
authors: Marks Luke, Abdullah Amir, Neo Clement, Arike Rauno, Krueger David, Torr Philip, Barez Fazl
conference: "Arxiv"
year: 2023
bibkey: marks2023interpreting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.08164"}
tags: ['Agentic', 'Fine Tuning', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Responsible AI', 'Training Techniques']
---
Reinforcement learning from human feedback (RLHF) is widely used to train large language models (LLMs). However it is unclear whether LLMs accurately learn the underlying preferences in human feedback data. We coin the term (textit)Learned Feedback Pattern (LFP) for patterns in an LLMs activations learned during RLHF that improve its performance on the fine-tuning task. We hypothesize that LLMs with LFPs accurately aligned to the fine-tuning feedback exhibit consistent activation patterns for outputs that would have received similar feedback during RLHF. To test this we train probes to estimate the feedback signal implicit in the activations of a fine-tuned LLM. We then compare these estimates to the true feedback measuring how accurate the LFPs are to the fine-tuning feedback. Our probes are trained on a condensed sparse and interpretable representation of LLM activations making it easier to correlate features of the input with our probes predictions. We validate our probes by comparing the neural features they correlate with positive feedback inputs against the features GPT-4 describes and classifies as related to LFPs. Understanding LFPs can help minimize discrepancies between LLM behavior and training objectives which is essential for the safety of LLMs.
