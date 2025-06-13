---
layout: publication
title: 'Hybrid Graphs For Table-and-text Based Question Answering Using Llms'
authors: Ankush Agarwal, Ganesh S, Chaitanya Devaguptapu
conference: "Arxiv"
year: 2025
bibkey: agarwal2025hybrid
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.17767"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'RAG', 'GPT', 'Pruning', 'Pretraining Methods', 'Fine-Tuning', 'Applications']
---
Answering questions that require reasoning and aggregation across both
structured (tables) and unstructured (raw text) data sources presents
significant challenges. Current methods rely on fine-tuning and high-quality,
human-curated data, which is difficult to obtain. Recent advances in Large
Language Models (LLMs) have shown promising results for multi-hop question
answering (QA) over single-source text data in a zero-shot setting, yet
exploration into multi-source Table-Text QA remains limited. In this paper, we
present a novel Hybrid Graph-based approach for Table-Text QA that leverages
LLMs without fine-tuning. Our method constructs a unified Hybrid Graph from
textual and tabular data, pruning information based on the input question to
provide the LLM with relevant context concisely. We evaluate our approach on
the challenging Hybrid-QA and OTT-QA datasets using state-of-the-art LLMs,
including GPT-3.5, GPT-4, and LLaMA-3. Our method achieves the best zero-shot
performance on both datasets, improving Exact Match scores by up to 10% on
Hybrid-QA and 5.4% on OTT-QA. Moreover, our approach reduces token usage by up
to 53% compared to the original context.
