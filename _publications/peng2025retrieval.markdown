---
layout: publication
title: 'CAFE: Retrieval Head-based Coarse-to-fine Information Seeking To Enhance Multi-document QA Capability'
authors: Han Peng, Jinhao Jiang, Zican Dong, Wayne Xin Zhao, Lei Fang
conference: "Arxiv"
year: 2025
bibkey: peng2025retrieval
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.10063"}
tags: ['Fine-Tuning', 'RAG', 'Model Architecture', 'Attention Mechanism', 'Prompting']
---
Advancements in Large Language Models (LLMs) have extended their input context length, yet they still struggle with retrieval and reasoning in long-context inputs. Existing methods propose to utilize the prompt strategy and retrieval head to alleviate this limitation. However, they still face challenges in balancing retrieval precision and recall, impacting their efficacy in answering questions. To address this, we introduce \\(\textbf\{CAFE\}\\), a two-stage coarse-to-fine method to enhance multi-document question-answering capacities. By gradually eliminating the negative impacts of background and distracting documents, CAFE makes the responses more reliant on the evidence documents. Initially, a coarse-grained filtering method leverages retrieval heads to identify and rank relevant documents. Then, a fine-grained steering method guides attention to the most relevant content. Experiments across benchmarks show CAFE outperforms baselines, achieving up to 22.1% and 13.7% SubEM improvement over SFT and RAG methods on the Mistral model, respectively.
