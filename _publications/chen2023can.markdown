---
layout: publication
title: 'Can Multimodal Large Language Models Truly Perform Multimodal In-context Learning?'
authors: Shuo Chen, Zhen Han, Bailan He, Jianzhe Liu, Mark Buckley, Yao Qin, Philip Torr, Volker Tresp, Jindong Gu
conference: "Arxiv"
year: 2023
bibkey: chen2023can
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2311.18021'}
  - {name: "Code", url: 'https://chenxshuo.github.io/m-icl/'}
tags: ['Has Code', 'Prompting', 'Multimodal Models', 'Reinforcement Learning', 'In-Context Learning']
---
Large Language Models (LLMs) with in-context learning (ICL) ability can
quickly adapt to a specific context given a few demonstrations (demos).
Recently, Multimodal Large Language Models (MLLMs) built upon LLMs have also
shown multimodal ICL ability, i.e., responding to queries given a few
multimodal demos, including images, queries, and answers. While ICL has been
extensively studied on LLMs, its research on MLLMs remains limited. One
essential question is whether these MLLMs can truly conduct multimodal ICL, or
if only the textual modality is necessary. We investigate this question by
examining two primary factors that influence ICL: 1) Demo content, i.e.,
understanding the influences of demo content in different modalities. 2) Demo
selection strategy, i.e., how to select better multimodal demos for improved
performance. Experiments revealed that multimodal ICL is predominantly driven
by the textual content whereas the visual information in the demos has little
influence. Interestingly, visual content is still necessary and useful for
selecting demos to increase performance. Motivated by our analysis, we propose
a simple yet effective approach, termed Mixed Modality In-Context Example
Selection (MMICES), which considers both visual and language modalities when
selecting demos. Extensive experiments are conducted to support our findings
and verify the improvement brought by our method. Code is available at
\url\{https://chenxshuo.github.io/m-icl/\}.
