---
layout: publication
title: Teaching Autoregressive Language Models Complex Tasks By Demonstration
authors: Recchia Gabriel
conference: "Arxiv"
year: 2021
bibkey: recchia2021teaching
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2109.02102"}
tags: ['GPT', 'Model Architecture', 'Pretraining Methods', 'Training Techniques', 'Transformer']
---
This paper demonstrates that by fine45;tuning an autoregressive language model (GPT45;Neo) on appropriately structured step45;by45;step demonstrations it is possible to teach it to execute a mathematical task that has previously proved difficult for Transformers 45; longhand modulo operations 45; with a relatively small number of examples. Specifically we fine45;tune GPT45;Neo to solve the numbers95;95;div95;remainder task from the DeepMind Mathematics Dataset; Saxton et al. (arXiv1904.01557) reported below 4037; accuracy on this task with 2 million training examples. We show that after fine45;tuning on 200 appropriately structured demonstrations of solving long division problems and reporting the remainders the smallest available GPT45;Neo model achieves over 8037; accuracy. This is achieved by constructing an appropriate dataset for fine45;tuning with no changes to the learning algorithm. These results suggest that fine45;tuning autoregressive language models on small sets of well45;crafted demonstrations may be a useful paradigm for enabling individuals without training in machine learning to coax such models to perform some kinds of complex multi45;step tasks.
