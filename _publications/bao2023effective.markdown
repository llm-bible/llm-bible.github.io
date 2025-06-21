---
layout: publication
title: 'Tallrec: An Effective And Efficient Tuning Framework To Align Large Language
  Model With Recommendation'
authors: Keqin Bao et al.
conference: Arxiv
year: 2023
citations: 125
bibkey: bao2023effective
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2305.00447'}, {name: Code,
    url: 'https://github.com/SAI990323/TALLRec'}]
tags: [RAG, Pre-Training, In-Context Learning, Prompting, Tools]
---
Large Language Models (LLMs) have demonstrated remarkable performance across
diverse domains, thereby prompting researchers to explore their potential for
use in recommendation systems. Initial attempts have leveraged the exceptional
capabilities of LLMs, such as rich knowledge and strong generalization through
In-context Learning, which involves phrasing the recommendation task as
prompts. Nevertheless, the performance of LLMs in recommendation tasks remains
suboptimal due to a substantial disparity between the training tasks for LLMs
and recommendation tasks, as well as inadequate recommendation data during
pre-training. To bridge the gap, we consider building a Large Recommendation
Language Model by tunning LLMs with recommendation data. To this end, we
propose an efficient and effective Tuning framework for Aligning LLMs with
Recommendation, namely TALLRec. We have demonstrated that the proposed TALLRec
framework can significantly enhance the recommendation capabilities of LLMs in
the movie and book domains, even with a limited dataset of fewer than 100
samples. Additionally, the proposed framework is highly efficient and can be
executed on a single RTX 3090 with LLaMA-7B. Furthermore, the fine-tuned LLM
exhibits robust cross-domain generalization. Our code and data are available at
https://github.com/SAI990323/TALLRec.