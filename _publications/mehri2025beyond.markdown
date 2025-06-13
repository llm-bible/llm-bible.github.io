---
layout: publication
title: 'Beyond Sample-level Feedback: Using Reference-level Feedback To Guide Data Synthesis'
authors: Shuhaib Mehri, Xiusi Chen, Heng Ji, Dilek Hakkani-tür
conference: "Arxiv"
year: 2025
bibkey: mehri2025beyond
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.04511'}
tags: ['Fine-Tuning', 'Tools', 'Model Architecture']
---
LLMs demonstrate remarkable capabilities in following natural language
instructions, largely due to instruction-tuning on high-quality datasets. While
synthetic data generation has emerged as a scalable approach for creating such
datasets, maintaining consistent quality standards remains challenging. Recent
approaches incorporate feedback to improve data quality, but typically operate
at the sample level, generating and applying feedback for each response
individually. In this work, we propose Reference-Level Feedback, a novel
methodology that instead collects feedback based on high-quality reference
samples from carefully curated seed data. We use this feedback to capture rich
signals of desirable characteristics and propagate it throughout the data
synthesis process. We present REFED, a dataset of 10K instruction-response
pairs synthesized using such feedback. We demonstrate the effectiveness of our
approach by showing that Llama-3.1-8B-Instruct finetuned on REFED achieves
state-of-the-art performance among similar-sized SFT-based models on AlpacaEval
2.0 and strong results on Arena-Hard. Through extensive experiments, we show
that our approach consistently outperforms traditional sample-level feedback
methods with significantly fewer feedback collections and improves performance
across different model architectures.
