---
layout: publication
title: 'Llms Can Generate A Better Answer By Aggregating Their Own Responses'
authors: Zichong Li, Xinyu Feng, Yuheng Cai, Zixuan Zhang, Tianyi Liu, Chen Liang, Weizhu Chen, Haoyu Wang, Tuo Zhao
conference: "Arxiv"
year: 2025
bibkey: li2025llms
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.04104"}
tags: ['Prompting', 'RAG', 'Training Techniques', 'Reinforcement Learning']
---
Large Language Models (LLMs) have shown remarkable capabilities across tasks,
yet they often require additional prompting techniques when facing complex
problems. While approaches like self-correction and response selection have
emerged as popular solutions, recent studies have shown these methods perform
poorly when relying on the LLM itself to provide feedback or selection
criteria. We argue this limitation stems from the fact that common LLM
post-training procedures lack explicit supervision for discriminative judgment
tasks. In this paper, we propose Generative Self-Aggregation (GSA), a novel
prompting method that improves answer quality without requiring the model's
discriminative capabilities. GSA first samples multiple diverse responses from
the LLM, then aggregates them to obtain an improved solution. Unlike previous
approaches, our method does not require the LLM to correct errors or compare
response quality; instead, it leverages the model's generative abilities to
synthesize a new response based on the context of multiple samples. While GSA
shares similarities with the self-consistency (SC) approach for response
aggregation, SC requires specific verifiable tokens to enable majority voting.
In contrast, our approach is more general and can be applied to open-ended
tasks. Empirical evaluation demonstrates that GSA effectively improves response
quality across various tasks, including mathematical reasoning, knowledge-based
problems, and open-ended generation tasks such as code synthesis and
conversational responses.
