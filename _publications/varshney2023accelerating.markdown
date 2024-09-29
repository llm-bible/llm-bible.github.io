---
layout: publication
title: Accelerating LLaMA Inference by Enabling Intermediate Layer Decoding via Instruction Tuning with LITE
authors: Varshney Neeraj, Chatterjee Agneet, Parmar Mihir, Baral Chitta
conference: "Arxiv"
year: 2023
bibkey: varshney2023accelerating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.18581"}
tags: ['Applications', 'Efficiency And Optimization', 'Language Modeling', 'Reinforcement Learning']
---
Large Language Models (LLMs) have achieved remarkable performance across a wide variety of natural language tasks; however their large size makes their inference slow and computationally expensive. Focusing on this problem we propose to instruction tune LLMs with additional explicit losses from the intermediate layers (LITE) and show that it enables these layers to acquire good generation ability without affecting the generation ability of the final layer. We perform dynamic confidence-based early exiting at token level from the intermediate layers which improves the efficiency of text generation without compromising the quality of the generation. We conduct comprehensive experiments by instruction tuning LLaMA-2 models on the Alpaca dataset and holistically evaluate on four different human-instruction test sets. We show that dynamic early exiting achieves consistent and considerable inference computation cost improvements (37.86 for 7B and 46.35 for 13B model) while maintaining the generation quality of the responses. We further conduct a thorough analysis of the results over several important aspects such as comparing the semantic similarity of the outputs and dissecting the efficiency improvements by comparing the number of tokens generated in the output. In summary our work contributes to improving the efficiency of LLM inference while maintaining the generation quality a crucial step en route to enabling their widespread adoption.
