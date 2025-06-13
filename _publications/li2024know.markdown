---
layout: publication
title: 'Know The Unknown: An Uncertainty-sensitive Method For LLM Instruction Tuning'
authors: Jiaqi Li, Yixuan Tang, Yi Yang
conference: "Arxiv"
year: 2024
bibkey: li2024know
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.10099"}
tags: ['GPT', 'Prompting', 'Applications', 'Model Architecture']
---
Large language models (LLMs) demonstrate remarkable capabilities but face challenges from hallucinations, which typically arise from insufficient knowledge or context. While instructing LLMs to acknowledge knowledge limitations by responding with "I don't know" appears promising, we find that models consistently struggle with admitting knowledge gaps. This challenge may originate from current instruction datasets that emphasise answer generation over knowledge boundary awareness. To address this limitation, we introduce Uncertainty-and-Sensitivity-Aware Tuning (US-Tuning), a novel two-stage approach for contextual question answering (QA). The first stage enhances LLMs' ability to recognise their knowledge boundaries, while the second stage reinforces instruction adherence through carefully designed causal prompts. Our experimental results demonstrate that US-Tuning not only significantly reduces incorrect answers in contextual QA but also improves models' faithfulness to their parametric knowledge, mitigating hallucinations in general QA tasks. Our fine-tuned Llama2-7B model achieves up to a 34.7% improvement in handling out-of-knowledge questions and outperforms GPT-4 by 4.2% in overall performance.
