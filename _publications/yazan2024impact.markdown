---
layout: publication
title: The Impact of Quantization on Retrieval-Augmented Generation An Analysis of Small LLMs
authors: Yazan Mert, Verberne Suzan, Situmeang Frederik
conference: "Arxiv"
year: 2024
bibkey: yazan2024impact
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.10251"}
tags: ['ARXIV', 'Efficiency And Optimization', 'LLM', 'Quantization']
---
Post-training quantization reduces the computational demand of Large Language Models (LLMs) but can weaken some of their capabilities. Since LLM abilities emerge with scale smaller LLMs are more sensitive to quantization. In this paper we explore how quantization affects smaller LLMs ability to perform retrieval-augmented generation (RAG) specifically in longer contexts. We chose personalization for evaluation because it is a challenging domain to perform using RAG as it requires long-context reasoning over multiple documents. We compare the original FP16 and the quantized INT4 performance of multiple 7B and 8B LLMs on two tasks while progressively increasing the number of retrieved documents to test how quantized models fare against longer contexts. To better understand the effect of retrieval we evaluate three retrieval models in our experiments. Our findings reveal that if a 7B LLM performs the task well quantization does not impair its performance and long-context reasoning capabilities. We conclude that it is possible to utilize RAG with quantized smaller LLMs.
