---
layout: publication
title: 'Generalization Bias In Large Language Model Summarization Of Scientific Research'
authors: Uwe Peters, Benjamin Chin-yee
conference: "Arxiv"
year: 2025
bibkey: peters2025generalization
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.00025'}
tags: ['GPT', 'Applications', 'Model Architecture', 'Prompting', 'Reinforcement Learning', 'Ethics and Bias']
---
Artificial intelligence chatbots driven by large language models (LLMs) have
the potential to increase public science literacy and support scientific
research, as they can quickly summarize complex scientific information in
accessible terms. However, when summarizing scientific texts, LLMs may omit
details that limit the scope of research conclusions, leading to
generalizations of results broader than warranted by the original study. We
tested 10 prominent LLMs, including ChatGPT-4o, ChatGPT-4.5, DeepSeek, LLaMA
3.3 70B, and Claude 3.7 Sonnet, comparing 4900 LLM-generated summaries to their
original scientific texts. Even when explicitly prompted for accuracy, most
LLMs produced broader generalizations of scientific results than those in the
original texts, with DeepSeek, ChatGPT-4o, and LLaMA 3.3 70B overgeneralizing
in 26 to 73% of cases. In a direct comparison of LLM-generated and
human-authored science summaries, LLM summaries were nearly five times more
likely to contain broad generalizations (OR = 4.85, 95% CI [3.06, 7.70]).
Notably, newer models tended to perform worse in generalization accuracy than
earlier ones. Our results indicate a strong bias in many widely used LLMs
towards overgeneralizing scientific conclusions, posing a significant risk of
large-scale misinterpretations of research findings. We highlight potential
mitigation strategies, including lowering LLM temperature settings and
benchmarking LLMs for generalization accuracy.
