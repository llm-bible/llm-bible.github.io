---
layout: publication
title: 'Large Language Models As Evolution Strategies'
authors: Lange Robert Tjarko, Tian Yingtao, Tang Yujin
conference: "Arxiv"
year: 2024
bibkey: lange2024large
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.18381"}
tags: ['Efficiency And Optimization', 'Fine Tuning', 'In Context Learning', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Training Techniques', 'Transformer']
---
Large Transformer models are capable of implementing a plethora of so-called in-context learning algorithms. These include gradient descent classification sequence completion transformation and improvement. In this work we investigate whether large language models (LLMs) which never explicitly encountered the task of black-box optimization are in principle capable of implementing evolutionary optimization algorithms. While previous works have solely focused on language-based task specification we move forward and focus on the zero-shot application of LLMs to black-box optimization. We introduce a novel prompting strategy consisting of least-to-most sorting of discretized population members and querying the LLM to propose an improvement to the mean statistic i.e. perform a type of black-box recombination operation. Empirically we find that our setup allows the user to obtain an LLM-based evolution strategy which we call EvoLLM that robustly outperforms baseline algorithms such as random search and Gaussian Hill Climbing on synthetic BBOB functions as well as small neuroevolution tasks. Hence LLMs can act as plug-in in-context recombination operators. We provide several comparative studies of the LLMs model size prompt strategy and context construction. Finally we show that one can flexibly improve EvoLLMs performance by providing teacher algorithm information via instruction fine-tuning on previously collected teacher optimization trajectories.
