---
layout: publication
title: Improving Translation Faithfulness Of Large Language Models Via Augmenting Instructions
authors: Chen Yijie, Liu Yijin, Meng Fandong, Chen Yufeng, Xu Jinan, Zhou Jie
conference: "Arxiv"
year: 2023
bibkey: chen2023improving
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2308.12674"}
tags: ['Applications', 'Attention Mechanism', 'Model Architecture', 'RAG', 'Reinforcement Learning', 'Transformer']
---
Large Language Models (LLMs) present strong general capabilities and a current compelling challenge is stimulating their specialized capabilities such as machine translation through low-cost instruction tuning. The standard instruction-following data is sequentially organized as the concatenation of an instruction an input and a response. As the attention mechanism of LLMs has limitations on local focus LLMs tend to focus more on the words or sentences nearby at each position. This leads to a high risk of instruction forgetting during decoding. To alleviate the above issues We propose SWIE (Segment-Weighted Instruction Embedding) and an instruction-following dataset OVERMISS. SWIE improves the model instruction understanding by adding a global instruction representation on the following input and response representations. OVERMISS improves model faithfulness by comparing over-translation and miss-translation results with the correct translation. We apply our methods to two main-stream open-source LLMs BLOOM and LLaMA. The experimental results demonstrate significant improvements in translation performance with SWIE based on BLOOMZ-3b particularly in zero-shot and long text translations due to reduced instruction forgetting risk. Additionally OVERMISS outperforms the baseline in translation performance (e.g. an increase in BLEU scores from 0.69 to 3.12 and an average improvement of 0.48 percentage comet scores for LLaMA-7b) with further enhancements seen in models combining OVERMISS and SWIE (e.g. the BLUE scores increase up to 0.56 from English to German across three different backbones) and both exhibit improvements in the faithfulness metric based on word alignment.
