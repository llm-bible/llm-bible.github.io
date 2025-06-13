---
layout: publication
title: 'Babel: Open Multilingual Large Language Models Serving Over 90% Of Global Speakers'
authors: Yiran Zhao, Chaoqun Liu, Yue Deng, Jiahao Ying, Mahani Aljunied, Zhaodonghui Li, Lidong Bing, Hou Pong Chan, Yu Rong, Deli Zhao, Wenxuan Zhang
conference: "Arxiv"
year: 2025
bibkey: zhao2025open
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.00865"}
tags: ['Fine-Tuning', 'RAG', 'Reinforcement Learning', 'Training Techniques', 'Pretraining Methods']
---
Large language models (LLMs) have revolutionized natural language processing
(NLP), yet open-source multilingual LLMs remain scarce, with existing models
often limited in language coverage. Such models typically prioritize
well-resourced languages, while widely spoken but under-resourced languages are
often overlooked. To address this disparity, we introduce \\(\texttt\{Babel\}\\), an
open multilingual LLM that covers the top 25 languages by number of speakers,
supports over 90% of the global population, and includes many languages
neglected by other open multilingual LLMs. Unlike traditional continue
pretraining approaches, Babel expands its parameter count through a layer
extension technique that elevates Babel's performance ceiling. We introduce two
variants: \\(\texttt\{Babel-9B\}\\), designed for efficient inference and
fine-tuning, and \\(\texttt\{Babel-83B\}\\), which sets a new standard for open
multilingual LLMs. Extensive evaluations on multilingual tasks demonstrate its
superior performance compared to open LLMs of comparable size. In addition,
using open-source supervised fine-tuning datasets, Babel achieves remarkable
performance, with Babel-9B-Chat leading among 10B-sized LLMs and Babel-83B-Chat
setting a new standard for multilingual tasks, reaching the same level of
commercial models.
