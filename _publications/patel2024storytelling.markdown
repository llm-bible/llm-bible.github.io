---
layout: publication
title: 'SWAG: Storytelling With Action Guidance'
authors: Zeeshan Patel, Karim El-refai, Jonathan Pei, Tianle Li
conference: "Arxiv"
year: 2024
bibkey: patel2024storytelling
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2402.03483'}
tags: ['GPT', 'Model Architecture']
---
Automated long-form story generation typically employs long-context large
language models (LLMs) for one-shot creation, which can produce cohesive but
not necessarily engaging content. We introduce Storytelling With Action
Guidance (SWAG), a novel approach to storytelling with LLMs. Our approach
frames story writing as a search problem through a two-model feedback loop: one
LLM generates story content, and another auxiliary LLM is used to choose the
next best "action" to steer the story's future direction. Our results show that
SWAG can substantially outperform previous end-to-end story generation
techniques when evaluated by GPT-4 and through human evaluation. Our SWAG
pipeline using only small open-source models surpasses GPT-3.5-Turbo.
