---
layout: publication
title: 'Vector-icl: In-context Learning With Continuous Vector Representations'
authors: Yufan Zhuang, Chandan Singh, Liyuan Liu, Jingbo Shang, Jianfeng Gao
conference: "Arxiv"
year: 2024
bibkey: zhuang2024vector
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.05629'}
tags: ['Language Modeling', 'Few-Shot', 'Training Techniques', 'Applications', 'Prompting', 'In-Context Learning', 'Pretraining Methods']
---
Large language models (LLMs) have shown remarkable in-context learning (ICL)
capabilities on textual data. We explore whether these capabilities can be
extended to continuous vectors from diverse domains, obtained from black-box
pretrained encoders. By aligning input data with an LLM's embedding space
through lightweight projectors, we observe that LLMs can effectively process
and learn from these projected vectors, which we term Vector-ICL. In
particular, we find that pretraining projectors with general language modeling
objectives enables Vector-ICL, while task-specific finetuning further enhances
performance. In our experiments across various tasks and modalities, including
text reconstruction, numerical function regression, text classification,
summarization, molecule captioning, time-series classification, graph
classification, and fMRI decoding, Vector-ICL often surpasses both few-shot ICL
and domain-specific model or tuning. We further conduct analyses and case
studies, indicating the potential of LLMs to process vector representations
beyond traditional token-based paradigms.
