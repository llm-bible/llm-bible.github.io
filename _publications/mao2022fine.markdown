---
layout: publication
title: Fine45;tuning Pre45;trained Transformers Into Decaying Fast Weights
authors: Mao Huanru Henry
conference: "Arxiv"
year: 2022
bibkey: mao2022fine
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2210.04243"}
tags: ['Attention Mechanism', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Transformer']
---
Autoregressive Transformers are strong language models but incur O(T) complexity during per45;token generation due to the self45;attention mechanism. Recent work proposes kernel45;based methods to approximate causal self45;attention by replacing it with recurrent formulations with various update rules and feature maps to achieve O(1) time and memory complexity. We explore these approaches and find that they are unnecessarily complex and propose a simple alternative 45; decaying fast weights 45; that runs fast on GPU outperforms prior methods and retains 9937; of attentions performance for GPT45;2. We also show competitive performance on WikiText45;103 against more complex attention substitutes.
