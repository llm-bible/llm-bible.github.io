---
layout: publication
title: Magpie Alignment Data Synthesis From Scratch By Prompting Aligned Llms With Nothing
authors: Xu Zhangchen, Jiang Fengqing, Niu Luyao, Deng Yuntian, Poovendran Radha, Choi Yejin, Lin Bill Yuchen
conference: "Arxiv"
year: 2024
bibkey: xu2024alignment
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.08464"}
tags: ['Efficiency And Optimization', 'Fine Tuning', 'Prompting', 'Reinforcement Learning', 'Tools']
---
High45;quality instruction data is critical for aligning large language models (LLMs). Although some models such as Llama45;345;Instruct have open weights their alignment data remain private which hinders the democratization of AI. High human labor costs and a limited predefined scope for prompting prevent existing open45;source data creation methods from scaling effectively potentially limiting the diversity and quality of public alignment datasets. Is it possible to synthesize high45;quality instruction data at scale by extracting it directly from an aligned LLM We present a self45;synthesis method for generating large45;scale alignment data named Magpie. Our key observation is that aligned LLMs like Llama45;345;Instruct can generate a user query when we input only the left45;side templates up to the position reserved for user messages thanks to their auto45;regressive nature. We use this method to prompt Llama45;345;Instruct and generate 4 million instructions along with their corresponding responses. We perform a comprehensive analysis of the extracted data and select 300K high45;quality instances. To compare Magpie data with other public instruction datasets we fine45;tune Llama45;345;8B45;Base with each dataset and evaluate the performance of the fine45;tuned models. Our results indicate that in some tasks models fine45;tuned with Magpie perform comparably to the official Llama45;345;8B45;Instruct despite the latter being enhanced with 10 million data points through supervised fine45;tuning (SFT) and subsequent feedback learning. We also show that using Magpie solely for SFT can surpass the performance of previous public datasets utilized for both SFT and preference optimization such as direct preference optimization with UltraFeedback. This advantage is evident on alignment benchmarks such as AlpacaEval ArenaHard and WildBench.
