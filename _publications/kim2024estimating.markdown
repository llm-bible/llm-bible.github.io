---
layout: publication
title: Llmem Estimating GPU Memory Usage For Fine45;tuning Pre45;trained Llms
authors: Kim Taeho, Wang Yanming, Chaturvedi Vatshank, Gupta Lokesh, Kim Seyeon, Kwon Yongin, Ha Sangtae
conference: "Arxiv"
year: 2024
bibkey: kim2024estimating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.10933"}
tags: ['Model Architecture', 'Pretraining Methods', 'RAG', 'Tools', 'Transformer']
---
Fine45;tuning pre45;trained large language models (LLMs) with limited hardware presents challenges due to GPU memory constraints. Various distributed fine45;tuning methods have been proposed to alleviate memory constraints on GPU. However determining the most effective method for achieving rapid fine45;tuning while preventing GPU out45;of45;memory issues in a given environment remains unclear. To address this challenge we introduce LLMem a solution that estimates the GPU memory consumption when applying distributed fine45;tuning methods across multiple GPUs and identifies the optimal method. We conduct GPU memory usage estimation prior to fine45;tuning leveraging the fundamental structure of transformer45;based decoder models and the memory usage distribution of each method. Experimental results show that LLMem accurately estimates peak GPU memory usage on a single GPU with error rates of up to 1.637;. Additionally it shows an average error rate of 3.037; when applying distributed fine45;tuning methods to LLMs with more than a billion parameters on multi45;GPU setups.
