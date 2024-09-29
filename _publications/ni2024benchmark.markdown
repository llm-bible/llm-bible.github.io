---
layout: publication
title: Xl$^2$bench\: A Benchmark For Extremely Long Context Understanding With Long-range Dependencies
authors: Ni Xuanfan, Cai Hengyi, Wei Xiaochi, Wang Shuaiqiang, Yin Dawei, Li Piji
conference: "Arxiv"
year: 2024
bibkey: ni2024benchmark
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.05446"}
tags: ['RAG', 'Training Techniques']
---
Large Language Models (LLMs) have demonstrated remarkable performance across diverse tasks but are constrained by their small context window sizes. Various efforts have been proposed to expand the context window to accommodate even up to 200K input tokens. Meanwhile building high-quality benchmarks with much longer text lengths and more demanding tasks to provide comprehensive evaluations is of immense practical interest to facilitate long context understanding research of LLMs. However prior benchmarks create datasets that ostensibly cater to long-text comprehension by expanding the input of traditional tasks which falls short to exhibit the unique characteristics of long-text understanding including long dependency tasks and longer text length compatible with modern LLMs context window size. In this paper we introduce a benchmark for extremely long context understanding with long-range dependencies XL^2Bench which includes three scenarios Fiction Reading Paper Reading and Law Reading and four tasks of increasing complexity Memory Retrieval Detailed Understanding Overall Understanding and Open-ended Generation covering 27 subtasks in English and Chinese. It has an average length of 100K+ words (English) and 200K+ characters (Chinese). Evaluating six leading LLMs on XL^2Bench we find that their performance significantly lags behind human levels. Moreover the observed decline in performance across both the original and enhanced datasets underscores the efficacy of our approach to mitigating data contamination.
