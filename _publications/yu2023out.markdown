---
layout: publication
title: 'Seqgpt: An Out-of-the-box Large Language Model For Open Domain Sequence Understanding'
authors: Tianyu Yu, Chengyue Jiang, Chao Lou, Shen Huang, Xiaobin Wang, Wei Liu, Jiong Cai, Yangning Li, Yinghui Li, Kewei Tu, Hai-tao Zheng, Ningyu Zhang, Pengjun Xie, Fei Huang, Yong Jiang
conference: "Arxiv"
year: 2023
bibkey: yu2023out
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2308.10529'}
  - {name: "Code", url: 'https://github.com/Alibaba-NLP/SeqGPT'}
tags: ['Has Code', 'Language Modeling', 'GPT', 'Applications', 'Model Architecture', 'Prompting', 'Pretraining Methods']
---
Large language models (LLMs) have shown impressive ability for open-domain
NLP tasks. However, LLMs are sometimes too footloose for natural language
understanding (NLU) tasks which always have restricted output and input format.
Their performances on NLU tasks are highly related to prompts or demonstrations
and are shown to be poor at performing several representative NLU tasks, such
as event extraction and entity typing. To this end, we present SeqGPT, a
bilingual (i.e., English and Chinese) open-source autoregressive model
specially enhanced for open-domain natural language understanding. We express
all NLU tasks with two atomic tasks, which define fixed instructions to
restrict the input and output format but still ``open'' for arbitrarily varied
label sets. The model is first instruction-tuned with extremely fine-grained
labeled data synthesized by ChatGPT and then further fine-tuned by 233
different atomic tasks from 152 datasets across various domains. The
experimental results show that SeqGPT has decent classification and extraction
ability, and is capable of performing language understanding tasks on unseen
domains. We also conduct empirical studies on the scaling of data and model
size as well as on the transfer across tasks. Our model is accessible at
https://github.com/Alibaba-NLP/SeqGPT.
