---
layout: publication
title: Tuning Layernorm In Attention Towards Efficient Multi45;modal LLM Finetuning
authors: Zhao Bingchen, Tu Haoqin, Wei Chen, Mei Jieru, Xie Cihang
conference: "Arxiv"
year: 2023
bibkey: zhao2023tuning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.11420"}
tags: ['Attention Mechanism', 'Efficiency And Optimization', 'Fine Tuning', 'Model Architecture', 'RAG']
---
This paper introduces an efficient strategy to transform Large Language Models (LLMs) into Multi45;Modal Large Language Models (MLLMs). By conceptualizing this transformation as a domain adaptation process i.e. transitioning from text understanding to embracing multiple modalities we intriguingly note that within each attention block tuning LayerNorm suffices to yield strong performance. Moreover when benchmarked against other tuning approaches like full parameter finetuning or LoRA its benefits on efficiency are substantial. For example when compared to LoRA on a 13B model scale performance can be enhanced by an average of over 2037; across five multi45;modal tasks and meanwhile results in a significant reduction of trainable parameters by 41.937; and a decrease in GPU memory usage by 17.637;. On top of this LayerNorm strategy we showcase that selectively tuning only with conversational data can improve efficiency further. Beyond these empirical outcomes we provide a comprehensive analysis to explore the role of LayerNorm in adapting LLMs to the multi45;modal domain and improving the expressive power of the model.
