---
layout: publication
title: 'Logic Haystacks: Probing Llms Long-context Logical Reasoning (without Easily Identifiable Unrelated Padding)'
authors: Damien Sileo
conference: "Arxiv"
year: 2025
bibkey: sileo2025logic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.17169"}
tags: ['GPT', 'Model Architecture', 'Reinforcement Learning']
---
Large language models demonstrate promising long context processing
capabilities, with recent models touting context windows close to one million
tokens. However, the evaluations supporting these claims often involve simple
retrieval tasks or synthetic tasks padded with irrelevant text, which the
models may easily detect and discard. In this work, we generate lengthy
simplified English text with first-order logic representations spanning up to
2048 clauses (around 25k GPT-4 tokens). We formulate an evaluation task with
evidence retrieval for contradiction detection. The long, homogeneous text is
filled with distractors that are both hard to distinguish from relevant
evidences and provably not interfering with them. Our evaluation of evidence
retrieval shows that the effective context window is much smaller with
realistic distractors, already crumbling at 128 clauses.
