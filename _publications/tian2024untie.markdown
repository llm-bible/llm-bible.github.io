---
layout: publication
title: Untie The Knots An Efficient Data Augmentation Strategy For Long-context Pre-training In Language Models
authors: Tian Junfeng, Zheng Da, Cheng Yang, Wang Rui, Zhang Colin, Zhang Debing
conference: "Arxiv"
year: 2024
bibkey: tian2024untie
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.04774"}
tags: ['Attention Mechanism', 'Efficiency And Optimization', 'Model Architecture', 'Training Techniques', 'Transformer']
---
Large language models (LLM) have prioritized expanding the context window from which models can incorporate more information. However training models to handle long contexts presents significant challenges. These include the scarcity of high-quality natural long-context data the potential for performance degradation on short-context tasks and the reduced training efficiency associated with attention mechanisms. In this paper we introduce Untie the Knots ((textbfUtK)) a novel data augmentation strategy employed during the continue pre-training phase designed to efficiently enable LLMs to gain long-context capabilities without the need to modify the existing data mixture. In particular we chunk the documents shuffle the chunks and create a complex and knotted structure of long texts; LLMs are then trained to untie these knots and identify relevant segments within seemingly chaotic token sequences. This approach greatly improves the models performance by accurately attending to relevant information in long context and the training efficiency is also largely increased. We conduct extensive experiments on models with 7B and 72B parameters trained on 20 billion tokens demonstrating that UtK achieves 7537; and 84.537; accurracy on RULER at 128K context length significantly outperforming other long context strategies. The trained models will open-source for further research.
