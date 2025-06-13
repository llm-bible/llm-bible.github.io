---
layout: publication
title: 'Fastmem: Fast Memorization Of Prompt Improves Context Awareness Of Large Language Models'
authors: Junyi Zhu, Shuochen Liu, Yu Yu, Bo Tang, Yibo Yan, Zhiyu Li, Feiyu Xiong, Tong Xu, Matthew B. Blaschko
conference: "Arxiv"
year: 2024
bibkey: zhu2024fast
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.16069"}
  - {name: "Code", url: "https://github.com/IAAR-Shanghai/FastMem"}
tags: ['Prompting', 'Efficiency and Optimization', 'Applications', 'Has Code']
---
Large language models (LLMs) excel in generating coherent text, but they
often struggle with context awareness, leading to inaccuracies in tasks
requiring faithful adherence to provided information. We introduce FastMem, a
novel method designed to enhance instruction fine-tuned LLMs' context awareness
through fast memorization of the prompt. FastMem maximizes the likelihood of
the prompt before inference by updating only the last Feed-Forward Network
(FFN) module. This targeted approach ensures efficient optimization without
overfitting, significantly improving the model's ability to comprehend and
accurately follow the context. Our experiments demonstrate substantial gains in
reading comprehension, text summarization and adherence to output structures.
For instance, FastMem improves the accuracy of Llama 3-8B-Inst on the NQ-SWAP
dataset from 59.1% to 71.6%, and reduces the output structure failure rate of
Qwen 1.5-4B-Chat from 34.9% to 25.5%. Extensive experimental results highlight
FastMem's potential to offer a robust solution to enhance the reliability and
accuracy of LLMs in various applications. Our code is available at:
https://github.com/IAAR-Shanghai/FastMem
