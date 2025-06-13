---
layout: publication
title: 'Understanding Chain-of-thought In Llms Through Information Theory'
authors: Jean-francois Ton, Muhammad Faaiz Taufiq, Yang Liu
conference: "Arxiv"
year: 2024
bibkey: ton2024understanding
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.11984"}
tags: ['Tools']
---
Large Language Models (LLMs) have shown impressive performance in complex
reasoning tasks through Chain-of-Thought (CoT) reasoning, allowing models to
break down problems into manageable sub-tasks. However, existing CoT evaluation
techniques either require annotated CoT data or fall short in accurately
assessing intermediate reasoning steps, leading to high rates of false
positives. In this paper, we formalize CoT reasoning in LLMs through an
information-theoretic lens. Specifically, our framework quantifies the
`information gain' at each reasoning step, enabling the identification of
failure modes in LLMs without the need for expensive annotated datasets. We
demonstrate the efficacy of our approach through extensive experiments on toy
and GSM-8K data, where it significantly outperforms existing outcome-based
methods by providing more accurate insights into model performance on
individual tasks.
