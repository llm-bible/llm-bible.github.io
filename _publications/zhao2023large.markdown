---
layout: publication
title: 'Large Language Models Are Complex Table Parsers'
authors: Bowen Zhao, Changkai Ji, Yuejie Zhang, Wen He, Yingwen Wang, Qing Wang, Rui Feng, Xiaobo Zhang
conference: "Arxiv"
year: 2023
bibkey: zhao2023large
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.11521"}
tags: ['Transformer', 'GPT', 'Applications', 'Model Architecture', 'Pretraining Methods', 'Prompting']
---
With the Generative Pre-trained Transformer 3.5 (GPT-3.5) exhibiting
remarkable reasoning and comprehension abilities in Natural Language Processing
(NLP), most Question Answering (QA) research has primarily centered around
general QA tasks based on GPT, neglecting the specific challenges posed by
Complex Table QA. In this paper, we propose to incorporate GPT-3.5 to address
such challenges, in which complex tables are reconstructed into tuples and
specific prompt designs are employed for dialogues. Specifically, we encode
each cell's hierarchical structure, position information, and content as a
tuple. By enhancing the prompt template with an explanatory description of the
meaning of each tuple and the logical reasoning process of the task, we
effectively improve the hierarchical structure awareness capability of GPT-3.5
to better parse the complex tables. Extensive experiments and results on
Complex Table QA datasets, i.e., the open-domain dataset HiTAB and the aviation
domain dataset AIT-QA show that our approach significantly outperforms previous
work on both datasets, leading to state-of-the-art (SOTA) performance.
