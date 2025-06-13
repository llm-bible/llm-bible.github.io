---
layout: publication
title: 'Open-sql Framework: Enhancing Text-to-sql On Open-source Large Language Models'
authors: Xiaojun Chen, Tianle Wang, Tianhao Qiu, Jianbin Qin, Min Yang
conference: "Arxiv"
year: 2024
bibkey: chen2024open
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.06674"}
tags: ['Fine-Tuning', 'Tools', 'GPT', 'Model Architecture', 'Training Techniques', 'Pretraining Methods', 'Few-Shot', 'Prompting']
---
Despite the success of large language models (LLMs) in Text-to-SQL tasks,
open-source LLMs encounter challenges in contextual understanding and response
coherence. To tackle these issues, we present \ours, a systematic methodology
tailored for Text-to-SQL with open-source LLMs. Our contributions include a
comprehensive evaluation of open-source LLMs in Text-to-SQL tasks, the
\openprompt strategy for effective question representation, and novel
strategies for supervised fine-tuning. We explore the benefits of
Chain-of-Thought in step-by-step inference and propose the \openexample method
for enhanced few-shot learning. Additionally, we introduce token-efficient
techniques, such as \textbf\{Variable-length Open DB Schema\}, \textbf\{Target
Column Truncation\}, and \textbf\{Example Column Truncation\}, addressing
challenges in large-scale databases. Our findings emphasize the need for
further investigation into the impact of supervised fine-tuning on contextual
learning capabilities. Remarkably, our method significantly improved Llama2-7B
from 2.54% to 41.04% and Code Llama-7B from 14.54% to 48.24% on the
BIRD-Dev dataset. Notably, the performance of Code Llama-7B surpassed GPT-4
(46.35%) on the BIRD-Dev dataset.
