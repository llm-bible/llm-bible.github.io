---
layout: publication
title: 'Selective Self-to-supervised Fine-tuning For Generalization In Large Language Models'
authors: Sonam Gupta, Yatin Nandwani, Asaf Yehudai, Dinesh Khandelwal, Dinesh Raghu, Sachindra Joshi
conference: "Arxiv"
year: 2025
bibkey: gupta2025selective
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.08130"}
tags: ['Fine-Tuning', 'RAG', 'Training Techniques', 'Pretraining Methods']
---
Fine-tuning Large Language Models (LLMs) on specific datasets is a common
practice to improve performance on target tasks. However, this performance gain
often leads to overfitting, where the model becomes too specialized in either
the task or the characteristics of the training data, resulting in a loss of
generalization. This paper introduces Selective Self-to-Supervised Fine-Tuning
(S3FT), a fine-tuning approach that achieves better performance than the
standard supervised fine-tuning (SFT) while improving generalization. S3FT
leverages the existence of multiple valid responses to a query. By utilizing
the model's correct responses, S3FT reduces model specialization during the
fine-tuning stage. S3FT first identifies the correct model responses from the
training set by deploying an appropriate judge. Then, it fine-tunes the model
using the correct model responses and the gold response (or its paraphrase) for
the remaining samples. The effectiveness of S3FT is demonstrated through
experiments on mathematical reasoning, Python programming and reading
comprehension tasks. The results show that standard SFT can lead to an average
performance drop of up to \\(4.4\\) on multiple benchmarks, such as MMLU and
TruthfulQA. In contrast, S3FT reduces this drop by half, i.e. \\(2.5\\), indicating
better generalization capabilities than SFT while performing significantly
better on the fine-tuning tasks.
