---
layout: publication
title: Grounding Data Science Code Generation With Input45;output Specifications
authors: Wen Yeming, Yin Pengcheng, Shi Kensen, Michalewski Henryk, Chaudhuri Swarat, Polozov Alex
conference: "Arxiv"
year: 2024
bibkey: wen2024grounding
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.08073"}
tags: ['Applications', 'Prompting', 'RAG', 'Reinforcement Learning']
---
Large language models (LLMs) have recently demonstrated a remarkable ability to generate code from natural language (NL) prompts. However in the real world NL is often too ambiguous to capture the true intent behind programming problems requiring additional input45;output (I/O) specifications. Unfortunately LLMs can have difficulty aligning their outputs with both the NL prompt and the I/O specification. In this paper we give a way to mitigate this issue in the context of data science programming where tasks require explicit I/O specifications for clarity. Specifically we propose GIFT4Code a novel approach for the instruction fine45;tuning of LLMs with respect to I/O specifications. Our method leverages synthetic data produced by the LLM itself and utilizes execution45;derived feedback as a key learning signal. This feedback in the form of program I/O specifications is provided to the LLM to facilitate instruction fine45;tuning. We evaluated our approach on two challenging data science benchmarks Arcade and DS45;1000. The results demonstrate a significant improvement in the LLMs ability to generate code that is not only executable but also accurately aligned with user specifications substantially improving the quality of code generation for complex data science tasks.
