---
layout: publication
title: Know the Unknown An Uncertainty-Sensitive Method for LLM Instruction Tuning
authors: Li Jiaqi, Tang Yixuan, Yang Yi
conference: "Arxiv"
year: 2024
bibkey: li2024know
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.10099"}
tags: ['ARXIV', 'GPT', 'LLM', 'Model Architecture', 'Prompt', 'RAG']
---
Large language models (LLMs) have demonstrated remarkable capabilities across various tasks but still face challenges such as hallucinations. One potential reason for hallucinations is the lack of relevant knowledge or context. Thus a promising solution to mitigate this issue involves instructing LLMs to respond with I do not know when a question falls outside their knowledge domain or the provided context. However in this work we observed that LLMs struggle to admit their lack of knowledge primarily due to existing instruction datasets designed to encourage specific answers. To improve large language models capability to recognize the boundaries of their knowledge we propose a novel approach called uncertainty-sensitive tuning. This method involves two-stage training designed for uncertainty recognition and prompt-sensitive activation. In the first stage we guide the LLM to reject unknown questions. In the second stage we recover the decreased performance in QA tasks by incorporating designed causal instructions. By leveraging this method we aim to enhance the models ability to identify areas of uncertainty. The experimental results demonstrate that our proposed uncertainty-sensitive tuning method significantly improves the performance of the Llama2-chat-7B model. Specifically it achieves a substantial 34.7 improvement in handling questions involving knowledge gaps compared to the original model. Moreover our approach outperforms GPT-4 exhibiting a 9.4 increase in overall performance. We open-source the model and code on GitHub.
