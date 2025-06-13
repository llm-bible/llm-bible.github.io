---
layout: publication
title: 'Strategic Reasoning With Language Models'
authors: Kanishk Gandhi, Dorsa Sadigh, Noah D. Goodman
conference: "Arxiv"
year: 2023
bibkey: gandhi2023strategic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.19165"}
tags: ['Agentic', 'Training Techniques', 'Few-Shot', 'Tools', 'Pretraining Methods', 'Fine-Tuning', 'Prompting']
---
Strategic reasoning enables agents to cooperate, communicate, and compete
with other agents in diverse situations. Existing approaches to solving
strategic games rely on extensive training, yielding strategies that do not
generalize to new scenarios or games without retraining. Large Language Models
(LLMs), with their ability to comprehend and generate complex, context-rich
language, could prove powerful as tools for strategic gameplay. This paper
introduces an approach that uses pretrained LLMs with few-shot chain-of-thought
examples to enable strategic reasoning for AI agents. Our approach uses
systematically generated demonstrations of reasoning about states, values, and
beliefs to prompt the model. Using extensive variations of simple matrix games,
we show that strategies that are derived based on systematically generated
prompts generalize almost perfectly to new game structures, alternate
objectives, and hidden information. Additionally, we demonstrate our approach
can lead to human-like negotiation strategies in realistic scenarios without
any extra training or fine-tuning. Our results highlight the ability of LLMs,
guided by systematic reasoning demonstrations, to adapt and excel in diverse
strategic scenarios.
