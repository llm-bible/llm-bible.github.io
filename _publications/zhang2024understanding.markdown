---
layout: publication
title: 'Understanding The Dark Side Of Llms'' Intrinsic Self-correction'
authors: Qingjie Zhang, Han Qiu, Di Wang, Haoting Qian, Yiming Li, Tianwei Zhang, Minlie Huang
conference: "Arxiv"
year: 2024
bibkey: zhang2024understanding
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.14959"}
tags: ['Training Techniques', 'Model Architecture', 'GPT', 'Ethics and Bias', 'Pretraining Methods', 'Fine-Tuning', 'ACL', 'Prompting']
---
Intrinsic self-correction was proposed to improve LLMs' responses via
feedback prompts solely based on their inherent capability. However, recent
works show that LLMs' intrinsic self-correction fails without oracle labels as
feedback prompts. In this paper, we aim to interpret LLMs' intrinsic
self-correction for different tasks, especially for those failure cases. By
including one simple task and three complex tasks with state-of-the-art (SOTA)
LLMs like ChatGPT families (o1, 4o, 3.5-turbo) and Llama families (2-7B, 3-8B,
and 3.1-8B), we design three interpretation methods to reveal the dark side of
LLMs' intrinsic self-correction. We identify intrinsic self-correction can (1)
cause LLMs to waver both intermedia and final answers and lead to prompt bias
on simple factual questions; (2) introduce human-like cognitive bias on complex
tasks. In light of our findings, we also provide two simple yet effective
strategies for alleviation: question repeating and supervised fine-tuning with
a few samples. We open-source our work at https://x-isc.info/.
