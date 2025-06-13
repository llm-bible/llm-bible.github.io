---
layout: publication
title: 'LLMSR@XLLM25: An Empirical Study Of LLM For Structural Reasoning'
authors: Xinye Li, Mingqi Wan, Dianbo Sui
conference: "Arxiv"
year: 2025
bibkey: li2025empirical
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.12328'}
  - {name: "Code", url: 'https://github.com/asdfo123/LLMSR-asdfo123'}
tags: ['Has Code', 'Few-Shot', 'RAG', 'Training Techniques', 'Fine-Tuning', 'Prompting', 'Pretraining Methods']
---
We present Team asdfo123's submission to the LLMSR@XLLM25 shared task, which evaluates large language models on producing fine-grained, controllable, and interpretable reasoning processes. Systems must extract all problem conditions, decompose a chain of thought into statement-evidence pairs, and verify the logical validity of each pair. Leveraging only the off-the-shelf Meta-Llama-3-8B-Instruct, we craft a concise few-shot, multi-turn prompt that first enumerates all conditions and then guides the model to label, cite, and adjudicate every reasoning step. A lightweight post-processor based on regular expressions normalises spans and enforces the official JSON schema. Without fine-tuning, external retrieval, or ensembling, our method ranks 5th overall, achieving macro F1 scores on par with substantially more complex and resource-consuming pipelines. We conclude by analysing the strengths and limitations of our approach and outlining directions for future research in structural reasoning with LLMs. Our code is available at https://github.com/asdfo123/LLMSR-asdfo123.
