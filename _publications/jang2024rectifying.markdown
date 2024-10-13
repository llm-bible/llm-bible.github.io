---
layout: publication
title: 'Rectifying Demonstration Shortcut In In-context Learning'
authors: Jang Joonwon, Jang Sanghwan, Kweon Wonbin, Jeon Minjin, Yu Hwanjo
conference: "Arxiv"
year: 2024
bibkey: jang2024rectifying
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.09488"}
tags: ['GPT', 'In Context Learning', 'Model Architecture', 'Prompting']
---
Large language models (LLMs) are able to solve various tasks with only a few
demonstrations utilizing their in-context learning (ICL) abilities. However,
LLMs often rely on their pre-trained semantic priors of demonstrations rather
than on the input-label relationships to proceed with ICL prediction. In this
work, we term this phenomenon as the 'Demonstration Shortcut'. While previous
works have primarily focused on improving ICL prediction results for predefined
tasks, we aim to rectify the Demonstration Shortcut, thereby enabling the LLM
to effectively learn new input-label relationships from demonstrations. To
achieve this, we introduce In-Context Calibration, a demonstration-aware
calibration method. We evaluate the effectiveness of the proposed method in two
settings: (1) the Original ICL Task using the standard label space and (2) the
Task Learning setting, where the label space is replaced with semantically
unrelated tokens. In both settings, In-Context Calibration demonstrates
substantial improvements, with results generalized across three LLM families
(OPT, GPT, and Llama2) under various configurations.
