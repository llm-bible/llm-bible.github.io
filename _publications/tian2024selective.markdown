---
layout: publication
title: 'Selective Prompt Anchoring For Code Generation'
authors: Tian Yuan, Zhang Tianyi
conference: "Arxiv"
year: 2024
bibkey: tian2024selective
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.09121"}
  - {name: "Code", url: "https://github.com/magic-YuanTian/Selective-Prompt-Anchoring"}
tags: ['Applications', 'Attention Mechanism', 'GPT', 'Has Code', 'Model Architecture', 'Prompting', 'Reinforcement Learning', 'Transformer']
---
Recent advances in large language models (LLMs) such as Copilot and ChatGPT
have transformed software development by automating coding tasks. Despite these
advancements, challenges remain in reducing error rates and fully meeting user
expectations. Our empirical study reveals LLMs tend to dilute their
self-attention on the initial prompt as more code tokens are generated. We
hypothesize this self-attention dilution issue is one of the root causes of
inaccuracies in LLM-generated code. To mitigate this issue, we propose
Selective Prompt Anchoring (SPA). SPA amplifies the influence of the selected
parts in the initial prompt, which we refer to as ``anchored text'', during
code generation. Specifically, SPA calculates the logit distribution difference
with and without the anchored text. We prove this difference approximates the
anchored text's contextual contribution to the output logits. SPA creates an
augmented logit distribution by linearly combining the original logit
distribution and the logit difference. We evaluate SPA with five LLMs on four
benchmarks. Our results demonstrate that using SPA can consistently improve
Pass@1 rates by up to 9.7% in all settings. Notably, with selective text
anchoring, a small version of DeepSeek-Coder (6.7B) can achieve better
performance than an original much larger version (33B). Our code is available
at https://github.com/magic-YuanTian/Selective-Prompt-Anchoring.
