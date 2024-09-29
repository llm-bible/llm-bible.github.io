---
layout: publication
title: '"merge Conflicts!" Exploring The Impacts Of External Distractors To Parametric Knowledge Graphs'
authors: Qian Cheng, Zhao Xinran, Wu Sherry Tongshuang
conference: "Arxiv"
year: 2023
bibkey: qian2023exploring
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.08594"}
tags: ['Applications', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
Large language models (LLMs) acquire extensive knowledge during pre-training known as their parametric knowledge. However in order to remain up-to-date and align with human instructions LLMs inevitably require external knowledge during their interactions with users. This raises a crucial question How will LLMs respond when external knowledge interferes with their parametric knowledge To investigate this question we propose a framework that systematically elicits LLM parametric knowledge and introduces external knowledge. Specifically we uncover the impacts by constructing a parametric knowledge graph to reveal the different knowledge structures of LLMs and introduce external knowledge through distractors of varying degrees methods positions and formats. Our experiments on both black-box and open-source models demonstrate that LLMs tend to produce responses that deviate from their parametric knowledge particularly when they encounter direct conflicts or confounding changes of information within detailed contexts. We also find that while LLMs are sensitive to the veracity of external knowledge they can still be distracted by unrelated information. These findings highlight the risk of hallucination when integrating external knowledge even indirectly during interactions with current LLMs. All the data and results are publicly available.
