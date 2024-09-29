---
layout: publication
title: Eliminating Position Bias of Language Models A Mechanistic Approach
authors: Wang Ziqi, Zhang Hanlin, Li Xiner, Huang Kuan-hao, Han Chi, Ji Shuiwang, Kakade Sham M., Peng Hao, Ji Heng
conference: "Arxiv"
year: 2024
bibkey: wang2024eliminating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.01100"}
tags: ['Applications', 'Attention Mechanism', 'Ethics And Bias', 'GPT', 'Model Architecture', 'Multimodal Models', 'Prompting', 'RAG', 'Reinforcement Learning', 'Security', 'Training Techniques']
---
Position bias has proven to be a prevalent issue of modern language models (LMs) where the models prioritize content based on its position within the given context. This bias often leads to unexpected model failures and hurts performance robustness and reliability across various applications. Our mechanistic analysis attributes the position bias to two components employed in nearly all state-of-the-art LMs causal attention and relative positional encodings. Specifically we find that causal attention generally causes models to favor distant content while relative positional encodings like RoPE prefer nearby ones based on the analysis of retrieval-augmented question answering (QA). Further our empirical study on object detection reveals that position bias is also present in vision-language models (VLMs). Based on the above analyses we propose to ELIMINATE position bias caused by different input segment orders (e.g. options in LM-as-a-judge retrieved documents in QA) in a TRAINING-FREE ZERO-SHOT manner. Our method changes the causal attention to bidirectional attention between segments and utilizes model attention values to decide the relative orders of segments instead of using the order provided in input prompts therefore enabling Position-INvariant inferencE (PINE) at the segment level. By eliminating position bias models achieve better performance and reliability in downstream tasks where position bias widely exists such as LM-as-a-judge and retrieval-augmented QA. Notably PINE is especially useful when adapting LMs for evaluating reasoning pairs it consistently provides 8 to 10 percentage points performance gains in most cases and makes Llama-3-70B-Instruct perform even better than GPT-4-0125-preview on the RewardBench reasoning subset.
