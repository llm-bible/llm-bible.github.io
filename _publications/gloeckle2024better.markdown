---
layout: publication
title: 'Better & Faster Large Language Models Via Multi-token Prediction'
authors: Gloeckle Fabian, Idrissi Badr Youbi, Rozière Baptiste, Lopez-paz David, Synnaeve Gabriel
conference: "Arxiv"
year: 2024
bibkey: gloeckle2024better
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.19737"}
tags: ['Efficiency And Optimization', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Training Techniques']
---
"Large language models such as GPT and Llama are trained with a next-token prediction loss. In this work, we suggest that training language models to predict multiple future tokens at once results in higher sample efficiency. More specifically, at each position in the training corpus, we ask the model to predict the following n tokens using n independent output heads, operating on top of a shared model trunk. Considering multi-token prediction as an auxiliary training task, we measure improved downstream capabilities with no overhead in training time for both code and natural language models. The method is increasingly useful for larger model sizes, and keeps its appeal when training for multiple epochs. Gains are especially pronounced on generative benchmarks like coding, where our models consistently outperform strong baselines by several percentage points. Our 13B parameter models solves 12 &#37; more problems on HumanEval and 17 &#37; more on MBPP than comparable next-token models. Experiments on small algorithmic tasks demonstrate that multi-token prediction is favorable for the development of induction heads and algorithmic reasoning capabilities. As an additional benefit, models trained with 4-token prediction are up to 3 times faster at inference, even with large batch sizes."
