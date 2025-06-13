---
layout: publication
title: 'Short-path Prompting In Llms: Analyzing Reasoning Instability And Solutions For Robust Performance'
authors: Zuoli Tang, Junjie Ou, Kaiqin Hu, Chunwei Wu, Zhaoxin Huan, Chilin Fu, Xiaolu Zhang, Jun Zhou, Chenliang Li
conference: "Arxiv"
year: 2025
bibkey: tang2025short
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.09586"}
tags: ['Fine-Tuning', 'Training Techniques', 'Prompting', 'Pretraining Methods']
---
Recent years have witnessed significant progress in large language models'
(LLMs) reasoning, which is largely due to the chain-of-thought (CoT)
approaches, allowing models to generate intermediate reasoning steps before
reaching the final answer. Building on these advances, state-of-the-art LLMs
are instruction-tuned to provide long and detailed CoT pathways when responding
to reasoning-related questions. However, human beings are naturally cognitive
misers and will prompt language models to give rather short responses, thus
raising a significant conflict with CoT reasoning. In this paper, we delve into
how LLMs' reasoning performance changes when users provide short-path prompts.
The results and analysis reveal that language models can reason effectively and
robustly without explicit CoT prompts, while under short-path prompting, LLMs'
reasoning ability drops significantly and becomes unstable, even on
grade-school problems. To address this issue, we propose two approaches: an
instruction-guided approach and a fine-tuning approach, both designed to
effectively manage the conflict. Experimental results show that both methods
achieve high accuracy, providing insights into the trade-off between
instruction adherence and reasoning accuracy in current models.
