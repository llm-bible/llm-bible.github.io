---
layout: publication
title: Prosparse Introducing And Enhancing Intrinsic Activation Sparsity Within Large Language Models
authors: Song Chenyang, Han Xu, Zhang Zhengyan, Hu Shengding, Shi Xiyu, Li Kuai, Chen Chen, Liu Zhiyuan, Li Guangli, Yang Tao, Sun Maosong
conference: "Arxiv"
year: 2024
bibkey: song2024introducing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.13516"}
tags: ['Efficiency And Optimization', 'Pruning']
---
Activation sparsity refers to the existence of considerable weakly45;contributed elements among activation outputs. As a prevalent property of the models using the ReLU activation function activation sparsity has been proven a promising paradigm to boost model inference efficiency. Nevertheless most large language models (LLMs) adopt activation functions without intrinsic activation sparsity (e.g. GELU and Swish). Some recent efforts have explored introducing ReLU or its variants as the substitutive activation function to help LLMs achieve activation sparsity and inference acceleration but few can simultaneously obtain high sparsity and comparable model performance. This paper introduces a simple and effective sparsification method named ProSparse to push LLMs for higher activation sparsity while maintaining comparable performance. Specifically after substituting the activation function of LLMs with ReLU ProSparse adopts progressive sparsity regularization with a factor smoothly increasing along the multi45;stage sine curves. This can enhance activation sparsity and mitigate performance degradation by avoiding radical shifts in activation distributions. With ProSparse we obtain high sparsity of 89.3237; for LLaMA245;7B 88.8037; for LLaMA245;13B and 87.8937; for end45;size MiniCPM45;1B respectively achieving comparable performance to their original Swish45;activated versions. These present the most sparsely activated models among open45;source LLaMA versions and competitive end45;size models considerably surpassing ReluLLaMA45;7B (66.9837;) and ReluLLaMA45;13B (71.5637;). Our inference acceleration experiments further demonstrate the significant practical acceleration potential of LLMs with higher activation sparsity obtaining up to 4.52× inference speedup.
