---
layout: publication
title: 'Steering Large Language Models For Machine Translation Personalization'
authors: Daniel Scalena, Gabriele Sarti, Arianna Bisazza, Elisabetta Fersini, Malvina Nissim
conference: "Arxiv"
year: 2025
bibkey: scalena2025steering
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.16612'}
tags: ['Reinforcement Learning', 'Prompting', 'Applications', 'Tools']
---
High-quality machine translation systems based on large language models (LLMs) have simplified the production of personalized translations reflecting specific stylistic constraints. However, these systems still struggle in settings where stylistic requirements are less explicit and might be harder to convey via prompting. We explore various strategies for personalizing LLM-generated translations in low-resource settings, focusing on the challenging literary translation domain. We explore prompting strategies and inference-time interventions for steering model generations towards a personalized style, and propose a contrastive framework exploiting latent concepts extracted from sparse autoencoders to identify salient personalization properties. Our results show that steering achieves strong personalization while preserving translation quality. We further examine the impact of steering on LLM representations, finding model layers with a relevant impact for personalization are impacted similarly by multi-shot prompting and our steering method, suggesting similar mechanism at play.
