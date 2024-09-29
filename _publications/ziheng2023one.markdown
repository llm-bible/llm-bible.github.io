---
layout: publication
title: Aligner One Global Token Is Worth Millions Of Parameters When Aligning Large Language Models
authors: Ziheng Zhou University Of California, Los Angeles, Wu Yingnian University Of California, Los Angeles, Zhu Song-chun University Of California, Los Angeles, Terzopoulos Demetri University Of California, Los Angeles
conference: "Arxiv"
year: 2023
bibkey: ziheng2023one
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.05503"}
tags: ['Attention Mechanism', 'Efficiency And Optimization', 'Fine Tuning', 'Model Architecture', 'Pretraining Methods', 'Training Techniques']
---
We introduce Aligner a novel Parameter-Efficient Fine-Tuning (PEFT) method for aligning multi-billion-parameter-sized Large Language Models (LLMs). Aligner employs a unique design that constructs a globally shared set of tunable tokens that modify the attention of every layer. Remarkably with this method even when using one token accounting for a mere 5000 parameters Aligner can still perform comparably well to state-of-the-art LLM adaptation methods like LoRA that require millions of parameters. This capacity is substantiated in both instruction following and value alignment tasks. Besides the multiple order-of-magnitude improvement in parameter efficiency the insight Aligner provides into the internal mechanisms of LLMs is also valuable. The architectural features and efficacy of our method in addition to our experiments demonstrate that an LLM separates its internal handling of form and knowledge in a somewhat orthogonal manner. This finding promises to motivate new research into LLM mechanism understanding and value alignment.
