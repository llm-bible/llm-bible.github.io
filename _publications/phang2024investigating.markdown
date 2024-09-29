---
layout: publication
title: Investigating The Effectiveness Of Hypertuning Via Gisting
authors: Phang Jason
conference: "Arxiv"
year: 2024
bibkey: phang2024investigating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.16817"}
tags: ['Attention Mechanism', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques', 'Transformer']
---
Gisting (Mu et al. 2023) is a simple method for training models to compress information into fewer token representations using a modified attention mask and can serve as an economical approach to training Transformer45;based hypernetworks. We introduce HyperLlama a set of Gisting45;based hypernetworks built on Llama45;2 models that generates task45;specific soft prefixes based on few45;shot inputs. In experiments across P3 Super45;NaturalInstructions and Symbol Tuning datasets we show that HyperLlama models can effectively compress information from few45;shot examples into soft prefixes. However they still underperform multi45;task fine45;tuned language models with full attention over few45;shot in45;context examples. We also show that HyperLlama45;generated soft prefixes can serve as better initializations for further prefix tuning. Overall Gisting45;based hypernetworks are economical and easy to implement but have mixed empirical performance.
