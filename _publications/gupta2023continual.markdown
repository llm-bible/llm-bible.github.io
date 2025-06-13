---
layout: publication
title: 'Continual Pre-training Of Large Language Models: How To (re)warm Your Model?'
authors: Kshitij Gupta, Benjamin Thérien, Adam Ibrahim, Mats L. Richter, Quentin Anthony, Eugene Belilovsky, Irina Rish, Timothée Lesort
conference: "Arxiv"
year: 2023
bibkey: gupta2023continual
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2308.04014"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Pre-Training', 'Model Architecture']
---
Large language models (LLMs) are routinely pre-trained on billions of tokens,
only to restart the process over again once new data becomes available. A much
cheaper and more efficient solution would be to enable the continual
pre-training of these models, i.e. updating pre-trained models with new data
instead of re-training them from scratch. However, the distribution shift
induced by novel data typically results in degraded performance on past data.
Taking a step towards efficient continual pre-training, in this work, we
examine the effect of different warm-up strategies. Our hypothesis is that the
learning rate must be re-increased to improve compute efficiency when training
on a new dataset. We study the warmup phase of models pre-trained on the Pile
(upstream data, 300B tokens) as we continue to pre-train on SlimPajama
(downstream data, 297B tokens), following a linear warmup and cosine decay
schedule. We conduct all experiments on the Pythia 410M language model
architecture and evaluate performance through validation perplexity. We
experiment with different pre-training checkpoints, various maximum learning
rates, and various warmup lengths. Our results show that while rewarming models
first increases the loss on upstream and downstream data, in the longer run it
improves the downstream performance, outperforming models trained from
scratch\\(\unicode\{x2013\}\\)even for a large downstream dataset.
