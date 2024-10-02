---
layout: publication
title: 'Memochat: Tuning Llms To Use Memos For Consistent Long-range Open-domain Conversation'
authors: Lu Junru, An Siyu, Lin Mingbao, Pergola Gabriele, He Yulan, Yin Di, Sun Xing, Wu Yunsheng
conference: "Arxiv"
year: 2023
bibkey: lu2023tuning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2308.08239"}
  - {name: "Code", url: "https://github.com/LuJunru/MemoChat"}
tags: ['Has Code', 'Pretraining Methods', 'Tools']
---
'We propose MemoChat, a pipeline for refining instructions that enables large language models (LLMs) to effectively employ self-composed memos for maintaining consistent long-range open-domain conversations. We demonstrate a long-range open-domain conversation through iterative memorization-retrieval-response cycles. This requires us to carefully design tailored tuning instructions for each distinct stage. The instructions are reconstructed from a collection of public datasets to teach the LLMs to memorize and retrieve past dialogues with structured memos, leading to enhanced consistency when participating in future conversations. We invite experts to manually annotate a test set designed to evaluate the consistency of long-range conversations questions. Experiments on three testing scenarios involving both open-source and API-accessible chatbots at scale verify the efficacy of MemoChat, which outperforms strong baselines. Our codes, data and models are available here: https://github.com/LuJunru/MemoChat.'
