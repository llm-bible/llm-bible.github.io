---
layout: publication
title: 'Decoprompt : Decoding Prompts Reduces Hallucinations When Large Language Models Meet False Premises'
authors: Nan Xu, Xuezhe Ma
conference: "Arxiv"
year: 2024
bibkey: xu2024decoprompt
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.07457"}
tags: ['RAG', 'Prompting', 'Applications']
---
While large language models (LLMs) have demonstrated increasing power, they
have also called upon studies on their hallucinated outputs that deviate from
factually correct statements. In this paper, we focus on one important scenario
of false premises, where LLMs are distracted by misaligned claims although the
model possesses the required factual knowledge to answer original questions
accurately. Inspired by the observation that entropy of the false-premise
prompt is closely related to its likelihood to elicit hallucination generation,
we propose a new prompting algorithm, named DecoPrompt, to mitigate
hallucination. DecoPrompt leverages LLMs to "decode" the false-premise prompts
without really eliciting hallucination output from LLMs. We perform experiments
on two datasets, demonstrating that DecoPrompt can reduce hallucinations
effectively on outputs from different LLMs. Moreover, DecoPrompt exhibits
cross-model transferability, which facilitates its applications to scenarios
such as LLMs of large sizes or unavailable model logits.
