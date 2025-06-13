---
layout: publication
title: 'An Empirical Study Of Pre-trained Language Models In Simple Knowledge Graph Question Answering'
authors: Nan Hu, Yike Wu, Guilin Qi, Dehai Min, Jiaoyan Chen, Jeff Z. Pan, Zafar Ali
conference: "Arxiv"
year: 2023
bibkey: hu2023empirical
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2303.10368'}
tags: ['Attention Mechanism', 'Efficiency and Optimization', 'Distillation', 'GPT', 'Model Architecture', 'BERT', 'Tools', 'Applications']
---
Large-scale pre-trained language models (PLMs) such as BERT have recently
achieved great success and become a milestone in natural language processing
(NLP). It is now the consensus of the NLP community to adopt PLMs as the
backbone for downstream tasks. In recent works on knowledge graph question
answering (KGQA), BERT or its variants have become necessary in their KGQA
models. However, there is still a lack of comprehensive research and comparison
of the performance of different PLMs in KGQA. To this end, we summarize two
basic KGQA frameworks based on PLMs without additional neural network modules
to compare the performance of nine PLMs in terms of accuracy and efficiency. In
addition, we present three benchmarks for larger-scale KGs based on the popular
SimpleQuestions benchmark to investigate the scalability of PLMs. We carefully
analyze the results of all PLMs-based KGQA basic frameworks on these benchmarks
and two other popular datasets, WebQuestionSP and FreebaseQA, and find that
knowledge distillation techniques and knowledge enhancement methods in PLMs are
promising for KGQA. Furthermore, we test ChatGPT, which has drawn a great deal
of attention in the NLP community, demonstrating its impressive capabilities
and limitations in zero-shot KGQA. We have released the code and benchmarks to
promote the use of PLMs on KGQA.
