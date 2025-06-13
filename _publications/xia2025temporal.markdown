---
layout: publication
title: 'Leetcodedataset: A Temporal Dataset For Robust Evaluation And Efficient Training Of Code Llms'
authors: Yunhui Xia, Wei Shen, Yan Wang, Jason Klein Liu, Huifeng Sun, Siyue Wu, Jian Hu, Xiaolong Xu
conference: "Arxiv"
year: 2025
bibkey: xia2025temporal
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.14655"}
tags: ['Training Techniques', 'Tools', 'RAG', 'Pretraining Methods', 'Fine-Tuning']
---
We introduce LeetCodeDataset, a high-quality benchmark for evaluating and
training code-generation models, addressing two key challenges in LLM research:
the lack of reasoning-focused coding benchmarks and self-contained training
testbeds. By curating LeetCode Python problems with rich metadata, broad
coverage, 100+ test cases per problem, and temporal splits (pre/post July
2024), our dataset enables contamination-free evaluation and efficient
supervised fine-tuning (SFT). Experiments show reasoning models significantly
outperform non-reasoning counterparts, while SFT with only 2.6K model-generated
solutions achieves performance comparable to 110K-sample counterparts. The
dataset and evaluation framework are available on Hugging Face and Github.
