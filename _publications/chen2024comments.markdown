---
layout: publication
title: 'Comments As Natural Logic Pivots: Improve Code Generation Via Comment Perspective'
authors: Yijie Chen, Yijin Liu, Fandong Meng, Yufeng Chen, Jinan Xu, Jie Zhou
conference: "Arxiv"
year: 2024
bibkey: chen2024comments
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.07549"}
  - {name: "Code", url: "https://github.com/pppa2019/Mango"}
tags: ['Security', 'Training Techniques', 'Model Architecture', 'Tools', 'Reinforcement Learning', 'GPT', 'Has Code', 'Prompting', 'Applications']
---
Code generation aims to understand the problem description and generate
corresponding code snippets, where existing works generally decompose such
complex tasks into intermediate steps by prompting strategies, such as
Chain-of-Thought and its variants. While these studies have achieved some
success, their effectiveness is highly dependent on the capabilities of
advanced Large Language Models (LLMs) such as GPT-4, particularly in terms of
API calls, which significantly limits their practical applicability.
Consequently, how to enhance the code generation capabilities of small and
medium-scale code LLMs without significantly increasing training costs is an
appealing challenge. In this paper, we suggest that code comments are the
natural logic pivot between natural language and code language and propose
using comments to boost the code generation ability of code LLMs. Concretely,
we propose MANGO (comMents As Natural loGic pivOts), including a comment
contrastive training strategy and a corresponding logical comment decoding
strategy. Experiments are performed on HumanEval and MBPP, utilizing StarCoder
and WizardCoder as backbone models, and encompassing model parameter sizes
between 3B and 7B. The results indicate that MANGO significantly improves the
code pass rate based on the strong baselines. Meanwhile, the robustness of the
logical comment decoding strategy is notably higher than the Chain-of-thoughts
prompting. The code is publicly available at
\url\{https://github.com/pppa2019/Mango\}.
