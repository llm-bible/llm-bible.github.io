---
layout: publication
title: 'Bridging Writing Manner Gap In Visual Instruction Tuning By Creating Llm-aligned Instructions'
authors: Dong Jing, Nanyi Fei, Zhiwu Lu
conference: "Arxiv"
year: 2025
bibkey: jing2025bridging
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.18320"}
tags: ['RAG']
---
In the realm of Large Multi-modal Models (LMMs), the instruction quality
during the visual instruction tuning stage significantly influences the
performance of modality alignment. In this paper, we assess the instruction
quality from a unique perspective termed \textbf\{Writing Manner\}, which
encompasses the selection of vocabulary, grammar and sentence structure to
convey specific semantics. We argue that there exists a substantial writing
manner gap between the visual instructions and the base Large Language Models
(LLMs) within LMMs. This gap forces the pre-trained base LLMs to deviate from
their original writing styles, leading to capability degradation of both base
LLMs and LMMs. To bridge the writing manner gap while preserving the original
semantics, we propose directly leveraging the base LLM to align the writing
manner of soft-format visual instructions with that of the base LLM itself,
resulting in novel LLM-aligned instructions. The manual writing manner
evaluation results demonstrate that our approach successfully minimizes the
writing manner gap. By utilizing LLM-aligned instructions, the baseline models
LLaVA-7B and QwenVL demonstrate enhanced resistance to hallucinations and
non-trivial comprehensive improvements across all \\(15\\) visual and language
benchmarks.
