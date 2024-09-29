---
layout: publication
title: Ffn45;skipllm A Hidden Gem For Autoregressive Decoding With Adaptive Feed Forward Skipping
authors: Jaiswal Ajay, Hu Bodun, Yin Lu, Ro Yeonju, Liu Shiwei, Chen Tianlong, Akella Aditya
conference: "Arxiv"
year: 2024
bibkey: jaiswal2024ffn
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.03865"}
tags: ['Applications', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning']
---
Autoregressive Large Language Models (e.g. LLaMa GPTs) are omnipresent achieving remarkable success in language understanding and generation. However such impressive capability typically comes with a substantial model size which presents significant challenges for autoregressive token45;by45;token generation. To mitigate computation overload incurred during generation several early45;exit and layer45;dropping strategies have been proposed. Despite some promising success due to the redundancy across LLMs layers on metrics like Rough45;L/BLUE our careful knowledge45;intensive evaluation unveils issues such as generation collapse hallucination of wrong facts and noticeable performance drop even at the trivial exit ratio of 1045;1537; of layers. We attribute these errors primarily to ineffective handling of the KV cache through state copying during early45;exit. In this work we observed the saturation of computationally expensive feed45;forward blocks of LLM layers and proposed FFN45;SkipLLM which is a novel fine45;grained skip strategy of autoregressive LLMs. More specifically FFN45;SkipLLM is an input45;adaptive feed45;forward skipping strategy that can skip 2545;3037; of FFN blocks of LLMs with marginal change in performance on knowledge45;intensive generation tasks without any requirement to handle KV cache. Our extensive experiments and ablation across benchmarks like MT45;Bench Factoid45;QA and variable45;length text summarization illustrate how our simple and ease45;at45;use method can facilitate faster autoregressive decoding.
