---
layout: publication
title: BayLing Bridging Cross-lingual Alignment and Instruction Following through Interactive Translation for Large Language Models
authors: Zhang Shaolei, Fang Qingkai, Zhang Zhuocheng, Ma Zhengrui, Zhou Yan, Huang Langlin, Bu Mengyu, Gui Shangtong, Chen Yunji, Chen Xilin, Feng Yang
conference: "Arxiv"
year: 2023
bibkey: zhang2023bayling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2306.10968"}
tags: ['GPT', 'Model Architecture', 'Pretraining Methods', 'Training Techniques']
---
Large language models (LLMs) have demonstrated remarkable prowess in language understanding and generation. Advancing from foundation LLMs to instructionfollowing LLMs instruction tuning plays a vital role in aligning LLMs to human preferences. However the existing LLMs are usually focused on English leading to inferior performance in non-English languages. In order to improve the performance for non-English languages it is necessary to collect language-specific training data for foundation LLMs and construct language-specific instructions for instruction tuning both of which are heavy loads. To minimize human workload we propose to transfer the capabilities of language generation and instruction following from English to other languages through an interactive translation task. We have developed BayLing an instruction-following LLM by utilizing LLaMA as the foundation LLM and automatically constructing interactive translation instructions for instructing tuning. Extensive assessments demonstrate that BayLing achieves comparable performance to GPT-3.5-turbo despite utilizing a considerably smaller parameter size of only 13 billion. Experimental results on translation tasks show that BayLing achieves 95 of single-turn translation capability compared to GPT-4 with automatic evaluation and 96 of interactive translation capability compared to GPT-3.5-turbo with human evaluation. To estimate the performance on general tasks we created a multi-turn instruction test set called BayLing-80. The experimental results on BayLing-80 indicate that BayLing achieves 89 of performance compared to GPT-3.5-turbo. BayLing also demonstrates outstanding performance on knowledge assessment of Chinese GaoKao and English SAT second only to GPT-3.5-turbo among a multitude of instruction-following LLMs. Demo homepage code and models of BayLing are available.
