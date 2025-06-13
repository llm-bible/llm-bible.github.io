---
layout: publication
title: 'Large Language Models Are Active Critics In NLG Evaluation'
authors: Shuying Xu, Junjie Hu, Ming Jiang
conference: "Arxiv"
year: 2024
bibkey: xu2024large
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.10724'}
tags: ['Prompting']
---
The conventional paradigm of using large language models (LLMs) for natural
language generation (NLG) evaluation relies on pre-defined task definitions and
evaluation criteria, positioning LLMs as "passive critics" that strictly follow
developer-provided guidelines. However, human evaluators often apply implicit
criteria, and their expectations in practice can vary widely based on specific
end-user needs. Consequently, these rigid evaluation methods struggle to adapt
to diverse scenarios without extensive prompt customization. To address this,
we introduce Active-Critic, a novel LLM-based evaluator that transforms LLMs
into "active critics'' capable of adapting to diverse NLG tasks using limited
example data. Active-Critic consists of two stages: (1) self-inferring the
target NLG task and relevant evaluation criteria, and (2) dynamically
optimizing prompts to produce human-aligned scores along with detailed
justifications. Our experiments show that Active-Critic can generate nuanced,
context-aware evaluation criteria, enabling it to achieve superior alignment
with human judgments across multiple tasks.
