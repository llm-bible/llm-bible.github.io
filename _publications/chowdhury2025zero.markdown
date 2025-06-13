---
layout: publication
title: 'Zero-shot Verification-guided Chain Of Thoughts'
authors: Jishnu Ray Chowdhury, Cornelia Caragea
conference: "Arxiv"
year: 2025
bibkey: chowdhury2025zero
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.13122"}
tags: ['Prompting', 'Few-Shot']
---
Previous works have demonstrated the effectiveness of Chain-of-Thought (COT)
prompts and verifiers in guiding Large Language Models (LLMs) through the space
of reasoning. However, most such studies either use a fine-tuned verifier or
rely on manually handcrafted few-shot examples. In contrast, in this paper, we
focus on LLM-based self-verification of self-generated reasoning steps via COT
prompts in a completely zero-shot regime. To explore this setting, we design a
new zero-shot prompt, which we call COT STEP, to aid zero-shot decomposition of
reasoning steps and design two new zero-shot prompts for LLM-based verifiers.
We evaluate the verifiers' ability to classify the correctness of reasoning
chains and explore different ways to use verifier scores in guiding reasoning
for various mathematical and commonsense reasoning tasks with different LLMs.
