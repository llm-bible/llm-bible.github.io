---
layout: publication
title: 'Raas: Reasoning-aware Attention Sparsity For Efficient LLM Reasoning'
authors: Junhao Hu, Wenrui Huang, Weidong Wang, Zhenwen Li, Tiancheng Hu, Zhixia Liu, Xusheng Chen, Tao Xie, Yizhou Shan
conference: "Arxiv"
year: 2025
bibkey: hu2025reasoning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.11147"}
tags: ['Model Architecture', 'Attention Mechanism']
---
Large Language Models (LLMs) have demonstrated strong capabilities across various domains, with recent advancements in challenging reasoning tasks such as mathematics and programming. However, solving reasoning tasks often requires an LLM to generate long sequences, incurring \\(O(N)\\) time and memory complexities per token, where \\(N\\) is the current sequence length. To reduce complexities, existing sparsity-based algorithms propose to retain Key-Value (KV) vectors, the intermediate representations of only the most critical tokens. However, these algorithms struggle with the "impossible trinity" of accuracy, time, and memory. For example, the state-of-the-art algorithm, Quest, achieves high accuracy with \\(O(L)\\) time but \\(O(N)\\) memory (\\(L\\) is the cache budget, \\(L \ll N\\)). To address the "impossible trinity", in this paper, we identify a new attention pattern during the decode stage of reasoning tasks, where milestone tokens (analogous to lemmas in mathematical proofs) emerge, are utilized, and then become unimportant afterward. Based on this pattern, we propose a new algorithm RaaS that identifies milestone tokens and retains their KV vectors until they are no longer needed, achieving high accuracy with \\(O(L)\\) time and \\(O(L)\\) memory complexities.
