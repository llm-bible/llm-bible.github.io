---
layout: publication
title: Simultaneous Masking, Not Prompting Optimization: A Paradigm Shift In Fine-tuning Llms For Simultaneous Translation
authors: Raffel Matthew, Agostinelli Victor, Chen Lizhong
conference: "Arxiv"
year: 2024
bibkey: raffel2024simultaneous
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.10443"}
tags: ['Attention Mechanism', 'Efficiency And Optimization', 'Fine Tuning', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Training Techniques']
---
Large language models (LLMs) have achieved state-of-the-art performance in various language processing tasks motivating their adoption in simultaneous translation. Current fine-tuning methods to adapt LLMs for simultaneous translation focus on prompting optimization strategies using either data augmentation or prompt structure modifications. However these methods suffer from several issues such as unnecessarily expanded training sets computational inefficiency from dumping the key and value cache increased prompt sizes or restriction to a single decision policy. To eliminate these issues in this work we propose SimulMask a new paradigm for fine-tuning LLMs for simultaneous translation. It utilizes a novel attention mask approach that models simultaneous translation during fine-tuning by masking attention for a desired decision policy. Applying the proposed SimulMask on a Falcon LLM for the IWSLT 2017 dataset we have observed a significant translation quality improvement compared to state-of-the-art prompting optimization strategies on five language pairs while reducing the computational cost.
