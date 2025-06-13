---
layout: publication
title: 'Large Language Models Suffer From Their Own Output: An Analysis Of The Self-consuming Training Loop'
authors: Martin Briesch, Dominik Sobania, Franz Rothlauf
conference: "Arxiv"
year: 2023
bibkey: briesch2023large
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.16822"}
tags: ['RAG', 'Training Techniques', 'Tools']
---
Large Language Models (LLM) are already widely used to generate content for a
variety of online platforms. As we are not able to safely distinguish
LLM-generated content from human-produced content, LLM-generated content is
used to train the next generation of LLMs, giving rise to a self-consuming
training loop. From the image generation domain we know that such a
self-consuming training loop reduces both quality and diversity of images
finally ending in a model collapse. However, it is unclear whether this
alarming effect can also be observed for LLMs. Therefore, we present the first
study investigating the self-consuming training loop for LLMs. Further, we
propose a novel method based on logic expressions that allows us to
unambiguously verify the correctness of LLM-generated content, which is
difficult for natural language text. We find that the self-consuming training
loop produces correct outputs, however, the output declines in its diversity
depending on the proportion of the used generated data. Fresh data can slow
down this decline, but not stop it. Given these concerning results, we
encourage researchers to study methods to negate this process.
