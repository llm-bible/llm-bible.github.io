---
layout: publication
title: 'Improving The Reliability Of Llms: Combining Cot, RAG, Self-consistency, And Self-verification'
authors: Adarsh Kumar, Hwiyoon Kim, Jawahar Sai Nathani, Neil Roy
conference: "Arxiv"
year: 2025
bibkey: kumar2025improving
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.09031"}
tags: ['Prompting', 'RAG']
---
Hallucination, where large language models (LLMs) generate confident but incorrect or irrelevant information, remains a key limitation in their application to complex, open-ended tasks. Chain-of-thought (CoT) prompting has emerged as a promising method for improving multistep reasoning by guiding models through intermediate steps. However, CoT alone does not fully address the hallucination problem. In this work, we investigate how combining CoT with retrieval-augmented generation (RAG), as well as applying self-consistency and self-verification strategies, can reduce hallucinations and improve factual accuracy. By incorporating external knowledge sources during reasoning and enabling models to verify or revise their own outputs, we aim to generate more accurate and coherent responses. We present a comparative evaluation of baseline LLMs against CoT, CoT+RAG, self-consistency, and self-verification techniques. Our results highlight the effectiveness of each method and identify the most robust approach for minimizing hallucinations while preserving fluency and reasoning depth.
