---
layout: publication
title: 'Autowebglm: A Large Language Model-based Web Navigating Agent'
authors: Hanyu Lai, Xiao Liu, Iat Long Iong, Shuntian Yao, Yuxuan Chen, Pengbo Shen, Hao Yu, Hanchen Zhang, Xiaohan Zhang, Yuxiao Dong, Jie Tang
conference: "Arxiv"
year: 2024
bibkey: lai2024large
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2404.03648'}
  - {name: "Code", url: 'https://github.com/THUDM/AutoWebGLM'}
tags: ['Agentic', 'Has Code', 'Model Architecture', 'Training Techniques', 'GPT', 'Reinforcement Learning']
---
Large language models (LLMs) have fueled many intelligent web agents, but
most existing ones perform far from satisfying in real-world web navigation
tasks due to three factors: (1) the complexity of HTML text data (2)
versatility of actions on webpages, and (3) task difficulty due to the
open-domain nature of the web. In light of these challenges, we develop the
open AutoWebGLM based on ChatGLM3-6B. AutoWebGLM can serve as a powerful
automated web navigation agent that outperform GPT-4. Inspired by human
browsing patterns, we first design an HTML simplification algorithm to
represent webpages with vital information preserved succinctly. We then employ
a hybrid human-AI method to build web browsing data for curriculum training.
Finally, we bootstrap the model by reinforcement learning and rejection
sampling to further facilitate webpage comprehension, browser operations, and
efficient task decomposition by itself. For comprehensive evaluation, we
establish a bilingual benchmark -- AutoWebBench -- for real-world web
navigation tasks. We evaluate AutoWebGLM across diverse web navigation
benchmarks, demonstrating its potential to tackle challenging tasks in real
environments. Related code, model, and data are released at
\url\{https://github.com/THUDM/AutoWebGLM\}.
