---
layout: publication
title: 'Sparsity Meets Similarity: Leveraging Long-tail Distribution For Dynamic Optimized Token Representation In Multimodal Large Language Models'
authors: Gaotong Yu, Yi Chen, Jian Xu
conference: "Arxiv"
year: 2024
bibkey: yu2024sparsity
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.01162"}
tags: ['RAG', 'Efficiency and Optimization', 'Multimodal Models', 'Pruning']
---
Recently, multimodal large language models (MM-LLMs) have achieved
significant success in various tasks, but their high computational costs limit
widespread application. The main computational burden arises from processing
concatenated text and visual tokens in the LLM layer, where input token length
directly affects efficiency. Our analysis of visual tokens reveals that their
similarity to the CLS token follows a long-tail distribution, with only a few
showing high similarity. To address this, we propose a dynamic pruning
algorithm that identifies the inflection point in the visual CLS token
similarity curve, enabling effective trimming of visual markers to accelerate
model performance. Additionally, we perform a second round of pruning in the
LLM layer, filtering out low-correlation tokens through the interaction between
visual and textual features. Experimental results demonstrate that our method
achieves performance comparable to the original while utilizing only 22% of the
original token quantity. Our source code will be made publicly available upon
acceptance.
