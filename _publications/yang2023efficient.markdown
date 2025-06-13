---
layout: publication
title: 'Longqlora: Efficient And Effective Method To Extend Context Length Of Large Language Models'
authors: Jianxin Yang
conference: "Arxiv"
year: 2023
bibkey: yang2023efficient
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.04879"}
  - {name: "Code", url: "https://github.com/yangjianxin1/LongQLoRA"}
tags: ['Training Techniques', 'Model Architecture', 'Language Modeling', 'Fine-Tuning', 'Has Code', 'Applications', 'Attention Mechanism']
---
We present LongQLoRA, an efficient and effective method to extend context
length of large language models with less training resources. LongQLoRA
combines the advantages of Position Interpolation, QLoRA and Shift Short
Attention of LongLoRA. With a single 32GB V100 GPU, LongQLoRA can extend the
context length of LLaMA2 7B and 13B from 4096 to 8192 and even to 12k within
1000 finetuning steps. LongQLoRA achieves competitive perplexity performance on
PG19 and Proof-pile datasets, our model outperforms LongLoRA and is very close
to MPT-7B-8K within the evaluation context length of 8192. We collect and build
39k long instruction data to extend context length of Vicuna-13B from 4096 to
8192 and achieve good performance both in long and short context generation
task. We also do some ablation experiments to study the effect of LoRA rank,
finetuning steps and attention patterns in inference.The model weights,
training data and code are avaliable at
https://github.com/yangjianxin1/LongQLoRA.
