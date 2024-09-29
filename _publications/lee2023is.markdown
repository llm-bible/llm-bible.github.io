---
layout: publication
title: Is Attention Required For ICL? Exploring The Relationship Between Model Architecture And In-context Learning Ability
authors: Lee Ivan, Jiang Nan, Berg-kirkpatrick Taylor
conference: "Arxiv"
year: 2023
bibkey: lee2023is
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.08049"}
tags: ['Attention Mechanism', 'Efficiency And Optimization', 'In Context Learning', 'Language Modeling', 'Merging', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'RAG', 'Training Techniques', 'Transformer']
---
What is the relationship between model architecture and the ability to perform in-context learning In this empirical study we take the first steps toward answering this question. We evaluate thirteen model architectures capable of causal language modeling across a suite of synthetic in-context learning tasks. These selected architectures represent a broad range of paradigms including recurrent and convolution-based neural networks transformers state space model inspired and other emerging attention alternatives. We discover that all the considered architectures can perform in-context learning under a wider range of conditions than previously documented. Additionally we observe stark differences in statistical efficiency and consistency by varying the number of in-context examples and task difficulty. We also measure each architectures predisposition towards in-context learning when presented with the option to memorize rather than leverage in-context examples. Finally and somewhat surprisingly we find that several attention alternatives are sometimes competitive with or better in-context learners than transformers. However no single architecture demonstrates consistency across all tasks with performance either plateauing or declining when confronted with a significantly larger number of in-context examples than those encountered during gradient-based training.
