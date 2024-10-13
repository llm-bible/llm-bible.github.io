---
layout: publication
title: 'Mistral-c2f: Coarse To Fine Actor For Analytical And Reasoning Enhancement In RLHF And Effective-merged Llms'
authors: Zheng Chen, Sun Ke, Zhou Xun
conference: "Arxiv"
year: 2024
bibkey: zheng2024mistral
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.08657"}
tags: ['GPT', 'Merging', 'Model Architecture', 'Reinforcement Learning', 'Uncategorized']
---
Despite the advances in Large Language Models (LLMs), exemplified by models
like GPT-4 and Claude, smaller-scale LLMs such as Llama and Mistral often
struggle with generating in-depth and coherent dialogues. This paper presents a
novel two-step Coarse-to-Fine Actor model to address the inherent limitations
in conversational and analytical capabilities of small-sized LLMs. Our approach
begins with the Policy-based Coarse Actor, employing a technique we term
"Continuous Maximization". The Coarse Actor establishes an enhanced,
knowledge-rich pool adept at aligning with human preference styles in analysis
and reasoning. Through the RLHF process, it employs Continuous Maximization, a
strategy that dynamically and adaptively extends the output length limit,
enabling the generation of more detailed and analytical content. Subsequently,
the Fine Actor refines this analytical content, addressing the generation of
excessively redundant information from the Coarse Actor. We introduce a
"Knowledge Residue Merger" approach, refining the content from the Coarse Actor
and merging it with an existing Instruction model to improve quality,
correctness, and reduce redundancies. We applied our methodology to the popular
Mistral model, creating Mistral-C2F, which has demonstrated exceptional
performance across 11 general language tasks and the MT-Bench Dialogue task,
outperforming similar-scale models and even larger models with 13B and 30B
parameters. Our model has significantly improved conversational and analytical
reasoning abilities.
