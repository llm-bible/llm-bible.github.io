---
layout: publication
title: "What Matters In Transformers? Not All Attention Is Needed"
authors: He Shwai, Sun Guoheng, Shen Zheyu, Li Ang
conference: "Arxiv"
year: 2024
bibkey: he2024what
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.15786"}
  - {name: "Code", url: "https://github.com/Shwai-He/LLM-Drop"}
tags: ['Attention Mechanism', 'Efficiency And Optimization', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'Pruning', 'Reinforcement Learning', 'Transformer']
---
Scaling Transformer-based large language models (LLMs) has demonstrated promising performance across various tasks. However it also introduces redundant structures posing challenges for real-world deployment. Despite some recognition of redundancy in LLMs the variability of redundancy across different modules such as MLP and Attention layers is under-explored. In this work we investigate the varying redundancy across different modules within Transformers including Blocks MLP and Attention layers using a similarity-based metric. This metric operates on the premise that redundant structures produce outputs highly similar to their inputs. Surprisingly while attention layers are essential for transformers and distinguish them from other mainstream architectures we found that a large proportion of attention layers exhibit excessively high similarity and can be safely pruned without degrading performance leading to reduced memory and computation costs. Additionally we further propose a method that jointly drops Attention and MLP layers achieving improved performance and dropping ratios. Extensive experiments demonstrate the effectiveness of our methods e.g. Llama-3-70B maintains comparable performance even after pruning half of the attention layers. Our findings provide valuable insights for future network architecture design. The code is released at (url)https://github.com/Shwai-He/LLM-Drop\}."
