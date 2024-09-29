---
layout: publication
title: Tree Of Uncertain Thoughts Reasoning For Large Language Models
authors: Mo Shentong, Xin Miao
conference: "Arxiv"
year: 2023
bibkey: mo2023tree
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.07694"}
tags: ['Prompting', 'RAG', 'Reinforcement Learning', 'Tools']
---
While the recently introduced Tree of Thoughts (ToT) has heralded advancements in allowing Large Language Models (LLMs) to reason through foresight and backtracking for global decision-making it has overlooked the inherent local uncertainties in intermediate decision points or thoughts. These local uncertainties intrinsic to LLMs given their potential for diverse responses remain a significant concern in the reasoning process. Addressing this pivotal gap we introduce the Tree of Uncertain Thoughts (TouT) - a reasoning framework tailored for LLMs. Our TouT effectively leverages Monte Carlo Dropout to quantify uncertainty scores associated with LLMs diverse local responses at these intermediate steps. By marrying this local uncertainty quantification with global search algorithms TouT enhances the models precision in response generation. We substantiate our approach with rigorous experiments on two demanding planning tasks Game of 24 and Mini Crosswords. The empirical evidence underscores TouTs superiority over both ToT and chain-of-thought prompting methods.
