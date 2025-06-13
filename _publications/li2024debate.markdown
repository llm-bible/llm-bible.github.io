---
layout: publication
title: 'A Debate-driven Experiment On LLM Hallucinations And Accuracy'
authors: Ray Li, Tanishka Bagade, Kevin Martinez, Flora Yasmin, Grant Ayala, Michael Lam, Kevin Zhu
conference: "Arxiv"
year: 2024
bibkey: li2024debate
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.19485'}
tags: ['Security', 'Training Techniques', 'Model Architecture', 'Tools', 'Fine-Tuning', 'GPT', 'Prompting', 'Pretraining Methods']
---
Large language models (LLMs) have achieved a degree of success in generating
coherent and contextually relevant text, yet they remain prone to a significant
challenge known as hallucination: producing information that is not
substantiated by the input or external knowledge. Previous efforts to mitigate
hallucinations have focused on techniques such as fine-tuning models on
high-quality datasets, incorporating fact-checking mechanisms, and developing
adversarial training methods. While these approaches have shown some promise,
they often address the issue at the level of individual model outputs, leaving
unexplored the effects of inter-model interactions on hallucination. This study
investigates the phenomenon of hallucination in LLMs through a novel
experimental framework where multiple instances of GPT-4o-Mini models engage in
a debate-like interaction prompted with questions from the TruthfulQA dataset.
One model is deliberately instructed to generate plausible but false answers
while the other models are asked to respond truthfully. The experiment is
designed to assess whether the introduction of misinformation by one model can
challenge the truthful majority to better justify their reasoning, improving
performance on the TruthfulQA benchmark. The findings suggest that inter-model
interactions can offer valuable insights into improving the accuracy and
robustness of LLM outputs, complementing existing mitigation strategies.
