---
layout: publication
title: 'Iterselecttune: An Iterative Training Framework For Efficient Instruction-tuning Data Selection'
authors: Jielin Song, Siyu Liu, Bin Zhu, Yanghui Rao
conference: "Arxiv"
year: 2024
bibkey: song2024iterative
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.13464'}
tags: ['Training Techniques', 'GPT', 'Tools', 'Fine-Tuning', 'Model Architecture', 'Pretraining Methods']
---
As large language models (LLMs) continue to advance, instruction tuning has
become critical for improving their ability to generate accurate and
contextually appropriate responses. Although numerous instruction-tuning
datasets have been developed to enhance LLM performance, selecting high-quality
instruction data from large source datasets typically demands significant human
effort. In this work, we introduce \\(\textbf\{IterSelectTune\}\\), an efficient,
cost-effective iterative training policy for selecting high-quality instruction
data with no human involvement and limited reliance on GPT-4. By fine-tuning on
approximately 20% of the source data, our method consistently outperforms
models fine-tuned on the full dataset across multiple benchmarks and public
test datasets. These results highlight the effectiveness of our approach in
enhancing LLM performance while reducing the computational resources required
for instruction tuning.
