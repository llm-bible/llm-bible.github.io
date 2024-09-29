---
layout: publication
title: InvestLM A Large Language Model for Investment using Financial Domain Instruction Tuning
authors: Yang Yi, Tang Yixuan, Tam Kar Yan
conference: "Arxiv"
year: 2023
bibkey: yang2023investlm
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.13064"}
tags: ['Efficiency And Optimization', 'GPT', 'Model Architecture']
---
We present a new financial domain large language model InvestLM tuned on LLaMA-65B (Touvron et al. 2023) using a carefully curated instruction dataset related to financial investment. Inspired by less-is-more-for-alignment (Zhou et al. 2023) we manually curate a small yet diverse instruction dataset covering a wide range of financial related topics from Chartered Financial Analyst (CFA) exam questions to SEC filings to Stackexchange quantitative finance discussions. InvestLM shows strong capabilities in understanding financial text and provides helpful responses to investment related questions. Financial experts including hedge fund managers and research analysts rate InvestLMs response as comparable to those of state-of-the-art commercial models (GPT-3.5 GPT-4 and Claude-2). Zero-shot evaluation on a set of financial NLP benchmarks demonstrates strong generalizability. From a research perspective this work suggests that a high-quality domain specific LLM can be tuned using a small set of carefully curated instructions on a well-trained foundation model which is consistent with the Superficial Alignment Hypothesis (Zhou et al. 2023). From a practical perspective this work develops a state-of-the-art financial domain LLM with superior capability in understanding financial texts and providing helpful investment advice potentially enhancing the work efficiency of financial professionals. We release the model parameters to the research community.
