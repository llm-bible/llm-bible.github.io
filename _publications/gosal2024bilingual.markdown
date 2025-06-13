---
layout: publication
title: 'Bilingual Adaptation Of Monolingual Foundation Models'
authors: Gurpreet Charles Gosal, Yishi Charles Xu, Gokul Charles Ramakrishnan, Rituraj Charles Joshi, Avraham Charles Sheinin, Charles Zhiming, Chen, Biswajit Mishra, Natalia Vassilieva, Joel Hestness, Neha Sengupta, Sunil Kumar Sahu, Bokang Jia, Onkar Pandit, Satheesh Katipomu, Samta Kamboj, Samujjwal Ghosh, Rahul Pal, Parvez Mullah, Soundar Doraiswamy, Mohamed El Karim Chami, Preslav Nakov
conference: "Arxiv"
year: 2024
bibkey: gosal2024bilingual
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2407.12869'}
tags: ['Pre-Training', 'Training Techniques']
---
We present an efficient method for adapting a monolingual Large Language
Model (LLM) to another language, addressing challenges of catastrophic
forgetting and tokenizer limitations. We focus this study on adapting Llama 2
to Arabic. Our two-stage approach begins with expanding the vocabulary and
training only the embeddings matrix, followed by full model continual
pre-training on a bilingual corpus. By continually pre-training on a mix of
Arabic and English corpora, the model retains its proficiency in English while
acquiring capabilities in Arabic. Our approach results in significant
improvements in Arabic and slight enhancements in English, demonstrating
cost-effective cross-lingual transfer. We perform ablations on embedding
initialization techniques, data mix ratios, and learning rates and release a
detailed training recipe. To demonstrate generalizability of this approach we
also adapted Llama 3 8B to Arabic and Llama 2 13B to Hindi.
