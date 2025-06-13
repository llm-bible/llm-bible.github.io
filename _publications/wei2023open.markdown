---
layout: publication
title: 'Polylm: An Open Source Polyglot Large Language Model'
authors: Xiangpeng Wei, Haoran Wei, Huan Lin, Tianhao Li, Pei Zhang, Xingzhang Ren, Mei Li, Yu Wan, Zhiwei Cao, Binbin Xie, Tianxiang Hu, Shangjie Li, Binyuan Hui, Bowen Yu, Dayiheng Liu, Baosong Yang, Fei Huang, Jun Xie
conference: "Arxiv"
year: 2023
bibkey: wei2023open
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2307.06018"}
tags: ['Training Techniques', 'Reinforcement Learning', 'Pretraining Methods', 'Fine-Tuning', 'Pre-Training', 'Applications']
---
Large language models (LLMs) demonstrate remarkable ability to comprehend,
reason, and generate following nature language instructions. However, the
development of LLMs has been primarily focused on high-resource languages, such
as English, thereby limiting their applicability and research in other
languages. Consequently, we present PolyLM, a multilingual LLM trained on 640
billion (B) tokens, avaliable in two model sizes: 1.7B and 13B. To enhance its
multilingual capabilities, we 1) integrate bilingual data into training data;
and 2) adopt a curriculum learning strategy that increases the proportion of
non-English data from 30% in the first stage to 60% in the final stage during
pre-training. Further, we propose a multilingual self-instruct method which
automatically generates 132.7K diverse multilingual instructions for model
fine-tuning. To assess the model's performance, we collect several existing
multilingual tasks, including multilingual understanding, question answering,
generation, and translation. Extensive experiments show that PolyLM surpasses
other open-source models such as LLaMA and BLOOM on multilingual tasks while
maintaining comparable performance in English. Our models, alone with the
instruction data and multilingual benchmark, are available at:
\url\{https://modelscope.cn/models/damo/nlp_polylm_13b_text_generation\}.
