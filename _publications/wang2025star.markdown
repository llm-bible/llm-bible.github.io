---
layout: publication
title: 'STAR-1: Safer Alignment Of Reasoning Llms With 1K Data'
authors: Zijun Wang, Haoqin Tu, Yuhan Wang, Juncheng Wu, Jieru Mei, Brian R. Bartoldson, Bhavya Kailkhura, Cihang Xie
conference: "Arxiv"
year: 2025
bibkey: wang2025star
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.01903"}
tags: ['Fine-Tuning', 'Responsible AI', 'GPT', 'RAG', 'Model Architecture', 'Training Techniques', 'Pretraining Methods']
---
This paper introduces STAR-1, a high-quality, just-1k-scale safety dataset
specifically designed for large reasoning models (LRMs) like DeepSeek-R1. Built
on three core principles -- diversity, deliberative reasoning, and rigorous
filtering -- STAR-1 aims to address the critical needs for safety alignment in
LRMs. Specifically, we begin by integrating existing open-source safety
datasets from diverse sources. Then, we curate safety policies to generate
policy-grounded deliberative reasoning samples. Lastly, we apply a GPT-4o-based
safety scoring system to select training examples aligned with best practices.
Experimental results show that fine-tuning LRMs with STAR-1 leads to an average
40% improvement in safety performance across four benchmarks, while only
incurring a marginal decrease (e.g., an average of 1.1%) in reasoning ability
measured across five reasoning tasks. Extensive ablation studies further
validate the importance of our design principles in constructing STAR-1 and
analyze its efficacy across both LRMs and traditional LLMs. Our project page is
https://ucsc-vlaa.github.io/STAR-1.
