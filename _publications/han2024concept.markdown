---
layout: publication
title: 'Concept-reversed Winograd Schema Challenge: Evaluating And Improving Robust Reasoning In Large Language Models Via Abstraction'
authors: Kaiqiao Han, Tianqing Fang, Zhaowei Wang, Yangqiu Song, Mark Steedman
conference: "Arxiv"
year: 2024
bibkey: han2024concept
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.12040"}
tags: ['Security', 'Prompting']
---
While Large Language Models (LLMs) have showcased remarkable proficiency in
reasoning, there is still a concern about hallucinations and unreliable
reasoning issues due to semantic associations and superficial logical chains.
To evaluate the extent to which LLMs perform robust reasoning instead of
relying on superficial logical chains, we propose a new evaluation dataset, the
Concept-Reversed Winograd Schema Challenge (CR-WSC), based on the famous
Winograd Schema Challenge (WSC) dataset. By simply reversing the concepts to
those that are more associated with the wrong answer, we find that the
performance of LLMs drops significantly despite the rationale of reasoning
remaining the same. Furthermore, we propose Abstraction-of-Thought (AoT), a
novel prompt method for recovering adversarial cases to normal cases using
conceptual abstraction to improve LLMs' robustness and consistency in
reasoning, as demonstrated by experiments on CR-WSC.
