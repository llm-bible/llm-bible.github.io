---
layout: publication
title: Fairness45;aware Structured Pruning In Transformers
authors: Zayed Abdelrahman, Mordido Goncalo, Shabanian Samira, Baldini Ioana, Chandar Sarath
conference: "Arxiv"
year: 2023
bibkey: zayed2023fairness
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.15398"}
tags: ['Attention Mechanism', 'Bias Mitigation', 'Efficiency And Optimization', 'Ethics And Bias', 'Fairness', 'GPT', 'Language Modeling', 'Model Architecture', 'Pretraining Methods', 'Pruning', 'Training Techniques', 'Transformer']
---
The increasing size of large language models (LLMs) has introduced challenges in their training and inference. Removing model components is perceived as a solution to tackle the large model sizes however existing pruning methods solely focus on performance without considering an essential aspect for the responsible use of LLMs model fairness. It is crucial to address the fairness of LLMs towards diverse groups such as women Black people LGBTQ+ Jewish communities among others as they are being deployed and available to a wide audience. In this work first we investigate how attention heads impact fairness and performance in pre45;trained transformer45;based language models. We then propose a novel method to prune the attention heads that negatively impact fairness while retaining the heads critical for performance i.e. language modeling capabilities. Our approach is practical in terms of time and resources as it does not require fine45;tuning the final pruned and fairer model. Our findings demonstrate a reduction in gender bias by 1937; 19.537; 39.537; 34.737; 2337; and 837; for DistilGPT45;2 GPT45;2 GPT45;Neo of two different sizes GPT45;J and Llama 2 models respectively in comparison to the biased model with only a slight decrease in performance.
