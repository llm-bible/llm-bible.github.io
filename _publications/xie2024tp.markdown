---
layout: publication
title: 'Tp-eval: Tap Multimodal Llms'' Potential In Evaluation By Customizing Prompts'
authors: Yuxuan Xie, Tianhua Li, Wenqi Shao, Kaipeng Zhang
conference: "Arxiv"
year: 2024
bibkey: xie2024tp
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.18071'}
tags: ['Attention Mechanism', 'Model Architecture', 'Tools', 'Prompting', 'Multimodal Models', 'Reinforcement Learning', 'Ethics and Bias']
---
Recently, multimodal large language models (MLLMs) have received much
attention for their impressive capabilities. The evaluation of MLLMs is
becoming critical to analyzing attributes of MLLMs and providing valuable
insights. However, current benchmarks overlook the problem of prompt
sensitivity - minor prompt variations may lead to significant performance
fluctuations. Thus, inappropriate prompts may obscure the models' capabilities,
underestimating the models' performance. Moreover, different models have
different preferences for different prompts, and thus, using the same prompt
for all models will cause evaluation bias. This paper analyzes this deficiency
in existing benchmarks and further introduces a new evaluation framework named
TP-Eval, which introduces a prompt customization method to reduce evaluation
biases and tap models' potential. TP-Eval will rewrite the original prompts to
different customized prompts for different models. In particular, we propose
some well-designed modules for prompt customization tailored to the scenario of
MLLM evaluation. Extensive experiments demonstrate the effectiveness of our
approach to uncovering models' capabilities, and TP-Eval should benefit the
community in developing more comprehensive and convincing MLLM evaluation
benchmarks.
