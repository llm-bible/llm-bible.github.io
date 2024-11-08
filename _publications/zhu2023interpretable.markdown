---
layout: publication
title: 'Autodan: Interpretable Gradient-based Adversarial Attacks On Large Language Models'
authors: Zhu Sicheng, Zhang Ruiyi, An Bang, Wu Gang, Barrow Joe, Wang Zichao, Huang Furong, Nenkova Ani, Sun Tong
conference: "Arxiv"
year: 2023
bibkey: zhu2023interpretable
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.15140"}
tags: ['Interpretability And Explainability', 'Merging', 'Prompting', 'Responsible AI', 'Security', 'Training Techniques']
---
Safety alignment of Large Language Models (LLMs) can be compromised with
manual jailbreak attacks and (automatic) adversarial attacks. Recent studies
suggest that defending against these attacks is possible: adversarial attacks
generate unlimited but unreadable gibberish prompts, detectable by
perplexity-based filters; manual jailbreak attacks craft readable prompts, but
their limited number due to the necessity of human creativity allows for easy
blocking. In this paper, we show that these solutions may be too optimistic. We
introduce AutoDAN, an interpretable, gradient-based adversarial attack that
merges the strengths of both attack types. Guided by the dual goals of
jailbreak and readability, AutoDAN optimizes and generates tokens one by one
from left to right, resulting in readable prompts that bypass perplexity
filters while maintaining high attack success rates. Notably, these prompts,
generated from scratch using gradients, are interpretable and diverse, with
emerging strategies commonly seen in manual jailbreak attacks. They also
generalize to unforeseen harmful behaviors and transfer to black-box LLMs
better than their unreadable counterparts when using limited training data or a
single proxy model. Furthermore, we show the versatility of AutoDAN by
automatically leaking system prompts using a customized objective. Our work
offers a new way to red-team LLMs and understand jailbreak mechanisms via
interpretability.
