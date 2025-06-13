---
layout: publication
title: 'Large Language Models Know What Makes Exemplary Contexts'
authors: Quanyu Long, Jianda Chen, Wenya Wang, Sinno Jialin Pan
conference: "Arxiv"
year: 2024
bibkey: long2024large
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.07505"}
tags: ['Agentic', 'Training Techniques', 'Few-Shot', 'Tools', 'Reinforcement Learning', 'Prompting', 'In-Context Learning']
---
In-context learning (ICL) has proven to be a significant capability with the
advancement of Large Language models (LLMs). By instructing LLMs using few-shot
demonstrative examples, ICL enables them to perform a wide range of tasks
without needing to update millions of parameters. This paper presents a unified
framework for LLMs that allows them to self-select influential in-context
examples to compose their contexts; self-rank candidates with different
demonstration compositions; self-optimize the demonstration selection and
ordering through reinforcement learning. Specifically, our method designs a
parameter-efficient retrieval head that generates the optimized demonstration
after training with rewards from LLM's own preference. Experimental results
validate the proposed method's effectiveness in enhancing ICL performance.
Additionally, our approach effectively identifies and selects the most
representative examples for the current task, and includes more diversity in
retrieval.
