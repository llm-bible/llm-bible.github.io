---
layout: publication
title: 'Large Language Model Can Be A Foundation For Hidden Rationale-based Retrieval'
authors: Luo Ji, Feixiang Guo, Teng Chen, Qingqing Gu, Xiaoyu Wang, Ningyuan Xi, Yihong Wang, Peng Yu, Yue Zhao, Hongyang Lei, Zhonglin Jiang, Yong Chen
conference: "Arxiv"
year: 2024
bibkey: ji2024large
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2412.16615'}
  - {name: "Code", url: 'https://github.com/flyfree5/LaHoRe'}
tags: ['Has Code', 'RAG', 'Efficiency and Optimization', 'Model Architecture', 'Tools', 'Prompting', 'Reinforcement Learning']
---
Despite the recent advancement in Retrieval-Augmented Generation (RAG)
systems, most retrieval methodologies are often developed for factual
retrieval, which assumes query and positive documents are semantically similar.
In this paper, we instead propose and study a more challenging type of
retrieval task, called hidden rationale retrieval, in which query and document
are not similar but can be inferred by reasoning chains, logic relationships,
or empirical experiences. To address such problems, an instruction-tuned Large
language model (LLM) with a cross-encoder architecture could be a reasonable
choice. To further strengthen pioneering LLM-based retrievers, we design a
special instruction that transforms the retrieval task into a generative task
by prompting LLM to answer a binary-choice question. The model can be
fine-tuned with direct preference optimization (DPO). The framework is also
optimized for computational efficiency with no performance degradation. We name
this retrieval framework by RaHoRe and verify its zero-shot and fine-tuned
performance superiority on Emotional Support Conversation (ESC), compared with
previous retrieval works. Our study suggests the potential to employ LLM as a
foundation for a wider scope of retrieval tasks. Our codes, models, and
datasets are available on https://github.com/flyfree5/LaHoRe.
