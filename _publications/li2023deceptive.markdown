---
layout: publication
title: Deceptive Semantic Shortcuts on Reasoning Chains How Far Can Models Go without Hallucination
authors: Li Bangzheng, Zhou Ben, Wang Fei, Fu Xingyu, Roth Dan, Chen Muhao
conference: "Arxiv"
year: 2023
bibkey: li2023deceptive
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.09702"}
tags: ['Ethics And Bias', 'Prompting']
---
Despite the recent advancement in large language models (LLMs) and their high performances across numerous benchmarks recent research has unveiled that LLMs suffer from hallucinations and unfaithful reasoning. This work studies a specific type of hallucination induced by semantic associations. Specifically we investigate to what extent LLMs take shortcuts from certain keyword/entity biases in the prompt instead of following the correct reasoning path. To quantify this phenomenon we propose a novel probing method and benchmark called EureQA. We start from questions that LLMs will answer correctly with utmost certainty and mask the important entity with evidence sentence recursively asking models to find masked entities according to a chain of evidence before answering the question. During the construction of the evidence we purposefully replace semantic clues (entities) that may lead to the correct answer with distractor clues (evidence) that will not directly lead to the correct answer but require a chain-like reasoning process. We evaluate if models can follow the correct reasoning chain instead of short-cutting through distractor clues. We find that existing LLMs lack the necessary capabilities to follow correct reasoning paths and resist the attempt of greedy shortcuts. We show that the distractor semantic associations often lead to model hallucination which is strong evidence that questions the validity of current LLM reasoning.
