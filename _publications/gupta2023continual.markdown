---
layout: publication
title: Continual Pre45;training Of Large Language Models How To (re)warm Your Model
authors: Gupta Kshitij, Thérien Benjamin, Ibrahim Adam, Richter Mats L., Anthony Quentin, Belilovsky Eugene, Rish Irina, Lesort Timothée
conference: "Arxiv"
year: 2023
bibkey: gupta2023continual
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2308.04014"}
tags: ['Efficiency And Optimization', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques']
---
Large language models (LLMs) are routinely pre45;trained on billions of tokens only to restart the process over again once new data becomes available. A much cheaper and more efficient solution would be to enable the continual pre45;training of these models i.e. updating pre45;trained models with new data instead of re45;training them from scratch. However the distribution shift induced by novel data typically results in degraded performance on past data. Taking a step towards efficient continual pre45;training in this work we examine the effect of different warm45;up strategies. Our hypothesis is that the learning rate must be re45;increased to improve compute efficiency when training on a new dataset. We study the warmup phase of models pre45;trained on the Pile (upstream data 300B tokens) as we continue to pre45;train on SlimPajama (downstream data 297B tokens) following a linear warmup and cosine decay schedule. We conduct all experiments on the Pythia 410M language model architecture and evaluate performance through validation perplexity. We experiment with different pre45;training checkpoints various maximum learning rates and various warmup lengths. Our results show that while rewarming models first increases the loss on upstream and downstream data in the longer run it improves the downstream performance outperforming models trained from scratchunicode123;x2013125;even for a large downstream dataset.
