---
layout: publication
title: 'Llava-prumerge: Adaptive Token Reduction For Efficient Large Multimodal Models'
authors: Shang Yuzhang, Cai Mu, Xu Bingxin, Lee Yong Jae, Yan Yan
conference: "Arxiv"
year: 2024
bibkey: shang2024llava
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.15388"}
  - {name: "Code", url: "https://llava-prumerge.github.io/"}
tags: ['Attention Mechanism', 'Has Code', 'Model Architecture', 'Multimodal Models', 'Pretraining Methods', 'RAG', 'Transformer']
---
Large Multimodal Models (LMMs) have shown significant visual reasoning capabilities by connecting a visual encoder and a large language model. LMMs typically take in a fixed and large amount of visual tokens such as the penultimate layer features in the CLIP visual encoder as the prefix content. Recent LMMs incorporate more complex visual inputs such as high-resolution images and videos which further increases the number of visual tokens significantly. However due to the inherent design of the Transformer architecture the computational costs of these models tend to increase quadratically with the number of input tokens. To tackle this problem we explore a token reduction mechanism that identifies significant spatial redundancy among visual tokens. In response we propose PruMerge a novel adaptive visual token reduction strategy that significantly reduces the number of visual tokens without compromising the performance of LMMs. Specifically to metric the importance of each token we exploit the sparsity observed in the visual encoder characterized by the sparse distribution of attention scores between the class token and visual tokens. This sparsity enables us to dynamically select the most crucial visual tokens to retain. Subsequently we cluster the selected (unpruned) tokens based on their key similarity and merge them with the unpruned tokens effectively supplementing and enhancing their informational content. Empirically when applied to LLaVA-1.5 our approach can compress the visual tokens by 14 times on average and achieve comparable performance across diverse visual question-answering and reasoning tasks. Code and checkpoints are at https://llava-prumerge.github.io/."
