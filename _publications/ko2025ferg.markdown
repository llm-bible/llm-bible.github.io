---
layout: publication
title: 'Ferg-llm : Feature Engineering By Reason Generation Large Language Models'
authors: Jeonghyun Ko, Gyeongyun Park, Donghoon Lee, Kyunam Lee
conference: "Arxiv"
year: 2025
bibkey: ko2025ferg
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.23371'}
tags: ['Efficiency and Optimization', 'Security', 'GPT', 'Model Architecture', 'Tools', 'Reinforcement Learning']
---
One of the key tasks in machine learning for tabular data is feature
engineering. Although it is vital for improving the performance of models, it
demands considerable human expertise and deep domain knowledge, making it
labor-intensive endeavor. To address this issue, we propose a novel framework,
\textbf\{FeRG-LLM\} (\textbf\{Fe\}ature engineering by \textbf\{R\}eason
\textbf\{G\}eneration \textbf\{L\}arge \textbf\{L\}anguage \textbf\{M\}odels), a large
language model designed to automatically perform feature engineering at an
8-billion-parameter scale. We have constructed two-stage conversational
dialogues that enable language models to analyze machine learning tasks and
discovering new features, exhibiting their Chain-of-Thought (CoT) capabilities.
We use these dialogues to fine-tune Llama 3.1 8B model and integrate Direct
Preference Optimization (DPO) to receive feedback improving quality of new
features and the model's performance. Our experiments show that FeRG-LLM
performs comparably to or better than Llama 3.1 70B on most datasets, while
using fewer resources and achieving reduced inference time. It outperforms
other studies in classification tasks and performs well in regression tasks.
Moreover, since it does not rely on cloud-hosted LLMs like GPT-4 with extra API
costs when generating features, it can be deployed locally, addressing security
concerns.
