---
layout: publication
title: Identifying Semantic Induction Heads to Understand In-Context Learning
authors: Ren Jie, Guo Qipeng, Yan Hang, Liu Dongrui, Zhang Quanshi, Qiu Xipeng, Lin Dahua
conference: "Arxiv"
year: 2024
bibkey: ren2024identifying
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.13055"}
tags: ['Applications', 'Attention Mechanism', 'Ethics And Bias', 'In Context Learning', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Transformer']
---
Although large language models (LLMs) have demonstrated remarkable performance the lack of transparency in their inference logic raises concerns about their trustworthiness. To gain a better understanding of LLMs we conduct a detailed analysis of the operations of attention heads and aim to better understand the in-context learning of LLMs. Specifically we investigate whether attention heads encode two types of relationships between tokens present in natural languages the syntactic dependency parsed from sentences and the relation within knowledge graphs. We find that certain attention heads exhibit a pattern where when attending to head tokens they recall tail tokens and increase the output logits of those tail tokens. More crucially the formulation of such semantic induction heads has a close correlation with the emergence of the in-context learning ability of language models. The study of semantic attention heads advances our understanding of the intricate operations of attention heads in transformers and further provides new insights into the in-context learning of LLMs.
