---
layout: publication
title: StreamingDialogue Prolonged Dialogue Learning via Long Context Compression with Minimal Losses
authors: Li Jia-nan, Tu Quan, Mao Cunli, Yu Zhengtao, Wen Ji-rong, Yan Rui
conference: "Arxiv"
year: 2024
bibkey: li2024streamingdialogue
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.08312"}
tags: ['Attention Mechanism', 'Efficiency And Optimization', 'Model Architecture', 'Pretraining Methods']
---
Standard Large Language Models (LLMs) struggle with handling dialogues with long contexts due to efficiency and consistency issues. According to our observation dialogue contexts are highly structured and the special token of (EoU) in dialogues has the potential to aggregate information. We refer to the EoU tokens as conversational attention sinks (conv-attn sinks). Accordingly we introduce StreamingDialogue which compresses long dialogue history into conv-attn sinks with minimal losses and thus reduces computational complexity quadratically with the number of sinks (i.e. the number of utterances). Current LLMs already demonstrate the ability to handle long context window e.g. a window size of 200k or more. To this end by compressing utterances into EoUs our method has the potential to handle more than 200k of utterances resulting in a prolonged dialogue learning. In order to minimize information losses from reconstruction after compression we design two learning strategies of short-memory reconstruction (SMR) and long-memory reactivation (LMR). Our method outperforms strong baselines in dialogue tasks and achieves a 4 times speedup while reducing memory usage by 18 times compared to dense attention recomputation.
