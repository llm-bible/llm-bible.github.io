---
layout: publication
title: 'Universal Item Tokenization For Transferable Generative Recommendation'
authors: Bowen Zheng, Hongyu Lu, Yu Chen, Wayne Xin Zhao, Ji-rong Wen
conference: "Arxiv"
year: 2025
bibkey: zheng2025universal
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.04405"}
tags: ['Tools', 'GPT', 'Model Architecture', 'Attention Mechanism', 'Tokenization', 'Pretraining Methods', 'Multimodal Models']
---
Recently, generative recommendation has emerged as a promising paradigm, attracting significant research attention. The basic framework involves an item tokenizer, which represents each item as a sequence of codes serving as its identifier, and a generative recommender that predicts the next item by autoregressively generating the target item identifier. However, in existing methods, both the tokenizer and the recommender are typically domain-specific, limiting their ability for effective transfer or adaptation to new domains. To this end, we propose UTGRec, a Universal item Tokenization approach for transferable Generative Recommendation. Specifically, we design a universal item tokenizer for encoding rich item semantics by adapting a multimodal large language model (MLLM). By devising tree-structured codebooks, we discretize content representations into corresponding codes for item tokenization. To effectively learn the universal item tokenizer on multiple domains, we introduce two key techniques in our approach. For raw content reconstruction, we employ dual lightweight decoders to reconstruct item text and images from discrete representations to capture general knowledge embedded in the content. For collaborative knowledge integration, we assume that co-occurring items are similar and integrate collaborative signals through co-occurrence alignment and reconstruction. Finally, we present a joint learning framework to pre-train and adapt the transferable generative recommender across multiple domains. Extensive experiments on four public datasets demonstrate the superiority of UTGRec compared to both traditional and generative recommendation baselines.
