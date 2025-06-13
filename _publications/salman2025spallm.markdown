---
layout: publication
title: 'Spallm-guard: Pairing SMS Spam Detection Using Open-source And Commercial Llms'
authors: Muhammad Salman, Muhammad Ikram, Nardine Basta, Mohamed Ali Kaafar
conference: "Arxiv"
year: 2025
bibkey: salman2025spallm
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2501.04985'}
tags: ['Few-Shot', 'Security', 'GPT', 'Training Techniques', 'Model Architecture', 'Fine-Tuning', 'Prompting', 'Reinforcement Learning', 'Pretraining Methods']
---
The increasing threat of SMS spam, driven by evolving adversarial techniques
and concept drift, calls for more robust and adaptive detection methods. In
this paper, we evaluate the potential of large language models (LLMs), both
open-source and commercial, for SMS spam detection, comparing their performance
across zero-shot, few-shot, fine-tuning, and chain-of-thought prompting
approaches. Using a comprehensive dataset of SMS messages, we assess the spam
detection capabilities of prominent LLMs such as GPT-4, DeepSeek, LLAMA-2, and
Mixtral. Our findings reveal that while zero-shot learning provides
convenience, it is unreliable for effective spam detection. Few-shot learning,
particularly with carefully selected examples, improves detection but exhibits
variability across models. Fine-tuning emerges as the most effective strategy,
with Mixtral achieving 98.6% accuracy and a balanced false positive and false
negative rate below 2%, meeting the criteria for robust spam detection.
Furthermore, we explore the resilience of these models to adversarial attacks,
finding that fine-tuning significantly enhances robustness against both
perceptible and imperceptible manipulations. Lastly, we investigate the impact
of concept drift and demonstrate that fine-tuned LLMs, especially when combined
with few-shot learning, can mitigate its effects, maintaining high performance
even on evolving spam datasets. This study highlights the importance of
fine-tuning and tailored learning strategies to deploy LLMs effectively for
real-world SMS spam detection
