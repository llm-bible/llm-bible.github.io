---
layout: publication
title: 'COMPKE: Complex Question Answering Under Knowledge Editing'
authors: Keyuan Cheng, Zijian Kan, Zhixian He, Zhuoran Zhang, Muhammad Asif Ali, Ke Xu, Lijie Hu, Di Wang
conference: "Arxiv"
year: 2025
bibkey: cheng2025complex
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2506.00829"}
  - {name: "Code", url: "https://github.com/kzjkzj666/CompKE"}
tags: ['Model Architecture', 'Reinforcement Learning', 'GPT', 'Has Code', 'Applications', 'Attention Mechanism']
---
Knowledge Editing, which efficiently modifies the knowledge in large language models, has gathered great attention. Current benchmarks primarily use multi-hop question answering to assess and analyze newly injected or updated knowledge. However, we argue that these benchmarks fail to effectively evaluate how well the updated models apply this knowledge in real-life scenarios, particularly when questions require complex reasoning, involving one-to-many relationships or multi-step logical intersections. To fill in this gap, we introduce a new benchmark, COMPKE: Complex Question Answering under Knowledge Editing, which includes 11,924 complex questions that reflect real-life situations. We conduct an extensive evaluation of four knowledge editing methods on COMPKE, revealing that their effectiveness varies notably across different models. For instance, MeLLo attains an accuracy of 39.47 on GPT-4O-MINI, but this drops sharply to 3.83 on QWEN2.5-3B. We further investigate the underlying causes of these disparities from both methodological and model-specific perspectives. The datasets are available at https://github.com/kzjkzj666/CompKE.
