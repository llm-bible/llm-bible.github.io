---
layout: publication
title: "Flashback:efficient Retrieval-augmented Language Modeling For Long Context Inference"
authors: Liu Runheng, Xiao Xingchen, Huang Heyan, Chi Zewen, Wu Zhijing
conference: "Arxiv"
year: 2024
bibkey: liu2024retrieval
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.04065"}
tags: ['Efficiency And Optimization', 'Fine Tuning', 'Language Modeling', 'Pretraining Methods', 'Prompting', 'RAG', 'Training Techniques']
---
Retrieval-Augmented Language Modeling (RALM) by integrating large language models (LLM) with relevant documents from an external corpus is a proven method for enabling the LLM to generate information beyond the scope of its pre-training corpus. Previous work utilizing retrieved content by simply prepending it to the input poses a high runtime issue which degrades the inference efficiency of the LLMs because they fail to use the Key-Value (KV) cache efficiently. In this paper we propose FlashBack a modular RALM designed to improve the inference efficiency of RALM with appending context pattern while maintaining decent performance after fine-tuning by Low-Rank Adaption. FlashBack appends retrieved documents at the end of the context for efficiently utilizing the KV cache instead of prepending them. And we introduce Marking Token as two special prompt tokens for marking the boundary of the appending context during fine-tuning. Our experiments on testing generation quality show that FlashBack can remain decent generation quality in perplexity. And the inference speed of FlashBack is up to 4(times) faster than the prepending counterpart on a 7B LLM (Llama 2) in the runtime test. Via bypassing unnecessary re-computation it demonstrates an advancement by achieving significantly faster inference speed and this heightened efficiency will substantially reduce inferential cost.
