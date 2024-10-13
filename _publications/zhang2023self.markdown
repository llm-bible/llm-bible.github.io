---
layout: publication
title: 'A Self-enhancement Approach For Domain-specific Chatbot Training Via Knowledge Mining And Digest'
authors: Zhang Ruohong, Gao Luyu, Zheng Chen, Fan Zhen, Lai Guokun, Zhang Zheng, Ai Fangzhou, Yang Yiming, Yang Hongxia
conference: "Arxiv"
year: 2023
bibkey: zhang2023self
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.10614"}
tags: ['Training Techniques', 'Uncategorized']
---
Large Language Models (LLMs), despite their great power in language
generation, often encounter challenges when dealing with intricate and
knowledge-demanding queries in specific domains. This paper introduces a novel
approach to enhance LLMs by effectively extracting the relevant knowledge from
domain-specific textual sources, and the adaptive training of a chatbot with
domain-specific inquiries. Our two-step approach starts from training a
knowledge miner, namely LLMiner, which autonomously extracts Question-Answer
pairs from relevant documents through a chain-of-thought reasoning process.
Subsequently, we blend the mined QA pairs with a conversational dataset to
fine-tune the LLM as a chatbot, thereby enriching its domain-specific expertise
and conversational capabilities. We also developed a new evaluation benchmark
which comprises four domain-specific text corpora and associated human-crafted
QA pairs for testing. Our model shows remarkable performance improvement over
generally aligned LLM and surpasses domain-adapted models directly fine-tuned
on domain corpus. In particular, LLMiner achieves this with minimal human
intervention, requiring only 600 seed instances, thereby providing a pathway
towards self-improvement of LLMs through model-synthesized training data.
