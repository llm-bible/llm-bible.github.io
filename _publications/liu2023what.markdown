---
layout: publication
title: What Large Language Models Bring to Text-rich VQA
authors: Liu Xuejing, Tang Wei, Ni Xinzhe, Lu Jinghui, Zhao Rui, Li Zechao, Tan Fei
conference: "Arxiv"
year: 2023
bibkey: liu2023what
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.07306"}
tags: ['Applications', 'Multimodal Models', 'RAG', 'Tools', 'Training Techniques']
---
Text-rich VQA namely Visual Question Answering based on text recognition in the images is a cross-modal task that requires both image comprehension and text recognition. In this work we focus on investigating the advantages and bottlenecks of LLM-based approaches in addressing this problem. To address the above concern we separate the vision and language modules where we leverage external OCR models to recognize texts in the image and Large Language Models (LLMs) to answer the question given texts. The whole framework is training-free benefiting from the in-context ability of LLMs. This pipeline achieved superior performance compared to the majority of existing Multimodal Large Language Models (MLLM) on four text-rich VQA datasets. Besides based on the ablation study we find that LLM brings stronger comprehension ability and may introduce helpful knowledge for the VQA problem. The bottleneck for LLM to address text-rich VQA problems may primarily lie in visual part. We also combine the OCR module with MLLMs and pleasantly find that the combination of OCR module with MLLM also works. Its worth noting that not all MLLMs can comprehend the OCR information which provides insights into how to train an MLLM that preserves the abilities of LLM.
