---
layout: publication
title: 'Rethinking The Effects Of Data Contamination In Code Intelligence'
authors: Zhen Yang, Hongyi Lin, Yifan He, Jie Xu, Zeyu Sun, Shuo Liu, Pengpeng Wang, Zhongxing Yu, Qingyuan Liang
conference: "Arxiv"
year: 2025
bibkey: yang2025rethinking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2506.02791"}
tags: ['Training Techniques', 'Model Architecture', 'GPT', 'Pretraining Methods', 'BERT', 'Fine-Tuning', 'Pre-Training', 'Applications']
---
In recent years, code intelligence has gained increasing importance in the field of automated software engineering. Meanwhile, the widespread adoption of Pretrained Language Models (PLMs) and Large Language Models (LLMs) has raised concerns regarding data contamination and its potential impact on model performance evaluation. This paper presents a systematic empirical study to investigate the fine-grained data contamination on code intelligence tasks. Our study involves diverse representative PLMs, namely RoBERTa and GPT-2, and LLMs, namely LLaMA and StarCoder, covering three major tasks: code translation, code generation, and code summarization. We categorize contamination scenarios into four types according to the code intelligence practice, namely input-only, output-only, unpaired, and paired contamination settings, and construct corresponding experimental and control groups for exploration.
  Experimental results show that, under the pre-training, fine-tuning, and inference paradigm adopted by PLMs, even deliberately injecting paired contamination does not lead to significant performance overestimation. But direct inference or small-scale fine-tuning uncovers the contamination effects. In contrast, LLMs with pre-training and inference paradigm are significantly affected by the paired contamination. Apart from the above, other contamination scenarios have no impact on both PLMs and LLMs. Our findings challenge the conventional belief that contamination inevitably leads to performance overestimation, providing new insights into the evaluation and deployment of code intelligence models.
