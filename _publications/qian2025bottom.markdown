---
layout: publication
title: 'Bottom-up Synthesis Of Knowledge-grounded Task-oriented Dialogues With Iteratively Self-refined Prompts'
authors: Kun Qian, Maximillian Chen, Siyan Li, Arpit Sharma, Zhou Yu
conference: "Arxiv"
year: 2025
bibkey: qian2025bottom
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.14375"}
tags: ['Prompting', 'Training Techniques']
---
Training conversational question-answering (QA) systems requires a
substantial amount of in-domain data, which is often scarce in practice. A
common solution to this challenge is to generate synthetic data. Traditional
methods typically follow a top-down approach, where a large language model
(LLM) generates multi-turn dialogues from a broad prompt. Although this method
produces coherent conversations, it offers limited fine-grained control over
the content and is susceptible to hallucinations. We introduce a bottom-up
conversation synthesis approach, where QA pairs are generated first and then
combined into a coherent dialogue. This method offers greater control and
precision by dividing the process into two distinct steps, allowing refined
instructions and validations to be handled separately. Additionally, this
structure allows the use of non-local models in stages that do not involve
proprietary knowledge, enhancing the overall quality of the generated data.
Both human and automated evaluations demonstrate that our approach produces
more realistic and higher-quality dialogues compared to top-down methods.
