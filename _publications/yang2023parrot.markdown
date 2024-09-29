---
layout: publication
title: Parrot Mind Towards Explaining The Complex Task Reasoning Of Pretrained Large Language Models With Template-content Structure
authors: Yang Haotong, Meng Fanxu, Lin Zhouchen, Zhang Muhan
conference: "Arxiv"
year: 2023
bibkey: yang2023parrot
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.05452"}
tags: ['Pretraining Methods', 'Training Techniques']
---
The pre-trained large language models (LLMs) have shown their extraordinary capacity to solve reasoning tasks even on tasks that require a complex process involving multiple sub-steps. However given the vast possible generation space of all the tasks how the pretrained model learns the reasoning ability remains an open question. We firstly propose that an intrinsic structural constraint on the generated sequence of language-based reasoning -- we called it template-content structure (T-C structure) -- is the key to explain why LLMs can solve a large number of complex reasoning problems with limited training data by showing this structure can reduce the possible space from exponential level to linear level. Furthermore by generalizing this structure to the hierarchical case we demonstrate that models can achieve task composition further reducing the space needed to learn from linear to logarithmic thereby effectively learning on complex reasoning involving multiple steps. We provide both examples and formal theory of our T-C structure. We also experimentally validate the existence of the T-C structure in some current LLMs and its effectiveness for reasoning.
