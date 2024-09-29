---
layout: publication
title: Ask More, Know Better: Reinforce-learned Prompt Questions For Decision Making With Large Language Models
authors: Yan Xue, Song Yan, Cui Xinyu, Christianos Filippos, Zhang Haifeng, Mguni David Henry, Wang Jun
conference: "Arxiv"
year: 2023
bibkey: yan2023ask
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.18127"}
tags: ['Prompting', 'Tools', 'Training Techniques']
---
Large language models (LLMs) demonstrate their promise in tackling complicated practical challenges by combining action-based policies with chain of thought (CoT) reasoning. Having high-quality prompts on hand however is vital to the frameworks effectiveness. Currently these prompts are handcrafted utilising extensive human labor resulting in CoT policies that frequently fail to generalise. Human intervention is also required to develop grounding functions that ensure low-level controllers appropriately process CoT reasoning. In this paper we propose a comprehensive training framework for complex task-solving incorporating human prior knowledge into the learning of action policies. To that purpose we offer a new leader-follower bilevel framework that is capable of learning to ask relevant questions (prompts) and subsequently undertaking reasoning to guide the learning of actions. The prompt policy is employed to make introspective revisions based on historical findings leading the CoT process to consider the anticipated goals and generate outputs that lead to decisive high-performing actions. The action policy subsequently learns to comprehend and integrate the CoT outputs to take actions. Our empirical data reveal that our framework outperforms leading methods in 5 decision-making tasks such as Overcooked and FourRoom.
