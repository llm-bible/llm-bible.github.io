---
layout: publication
title: 'BRIDGE: Benchmarking Large Language Models For Understanding Real-world Clinical Practice Text'
authors: Jiageng Wu, Bowen Gu, Ren Zhou, Kevin Xie, Doug Snyder, Yixing Jiang, Valentina Carducci, Richard Wyss, Rishi J Desai, Emily Alsentzer, Leo Anthony Celi, Adam Rodman, Sebastian Schneeweiss, Jonathan H. Chen, Santiago Romero-brufau, Kueiyu Joshua Lin, Jie Yang
conference: "Arxiv"
year: 2025
bibkey: wu2025benchmarking
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.19467'}
tags: ['GPT', 'Tools', 'Applications', 'Model Architecture', 'Reinforcement Learning']
---
Large language models (LLMs) hold great promise for medical applications and
are evolving rapidly, with new models being released at an accelerated pace.
However, current evaluations of LLMs in clinical contexts remain limited. Most
existing benchmarks rely on medical exam-style questions or PubMed-derived
text, failing to capture the complexity of real-world electronic health record
(EHR) data. Others focus narrowly on specific application scenarios, limiting
their generalizability across broader clinical use. To address this gap, we
present BRIDGE, a comprehensive multilingual benchmark comprising 87 tasks
sourced from real-world clinical data sources across nine languages. We
systematically evaluated 52 state-of-the-art LLMs (including DeepSeek-R1,
GPT-4o, Gemini, and Llama 4) under various inference strategies. With a total
of 13,572 experiments, our results reveal substantial performance variation
across model sizes, languages, natural language processing tasks, and clinical
specialties. Notably, we demonstrate that open-source LLMs can achieve
performance comparable to proprietary models, while medically fine-tuned LLMs
based on older architectures often underperform versus updated general-purpose
models. The BRIDGE and its corresponding leaderboard serve as a foundational
resource and a unique reference for the development and evaluation of new LLMs
in real-world clinical text understanding.
  The BRIDGE leaderboard:
https://huggingface.co/spaces/YLab-Open/BRIDGE-Medical-Leaderboard
