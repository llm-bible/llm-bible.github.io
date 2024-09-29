---
layout: publication
title: 'Syntax-guided Localized Self-attention By Constituency Syntactic Distance'
authors: Hou Shengyuan, Kai Jushi, Xue Haotian, Zhu Bingyu, Yuan Bo, Huang Longtao, Wang Xinbing, Lin Zhouhan
conference: "Arxiv"
year: 2022
bibkey: hou2022syntax
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2210.11759"}
tags: ['Applications', 'Attention Mechanism', 'Efficiency And Optimization', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Training Techniques', 'Transformer']
---
Recent works have revealed that Transformers are implicitly learning the syntactic information in its lower layers from data albeit is highly dependent on the quality and scale of the training data. However learning syntactic information from data is not necessary if we can leverage an external syntactic parser which provides better parsing quality with well-defined syntactic structures. This could potentially improve Transformers performance and sample efficiency. In this work we propose a syntax-guided localized self-attention for Transformer that allows directly incorporating grammar structures from an external constituency parser. It prohibits the attention mechanism to overweight the grammatically distant tokens over close ones. Experimental results show that our model could consistently improve translation performance on a variety of machine translation datasets ranging from small to large dataset sizes and with different source languages.
