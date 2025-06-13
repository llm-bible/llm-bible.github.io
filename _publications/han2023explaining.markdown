---
layout: publication
title: 'Explaining Emergent In-context Learning As Kernel Regression'
authors: Chi Han, Ziqi Wang, Han Zhao, Heng Ji
conference: "Arxiv"
year: 2023
bibkey: han2023explaining
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.12766"}
tags: ['Training Techniques', 'Model Architecture', 'In-Context Learning', 'Pretraining Methods', 'Transformer', 'Prompting', 'Pre-Training', 'Attention Mechanism']
---
Large language models (LLMs) have initiated a paradigm shift in transfer
learning. In contrast to the classic pretraining-then-finetuning procedure, in
order to use LLMs for downstream prediction tasks, one only needs to provide a
few demonstrations, known as in-context examples, without adding more or
updating existing model parameters. This in-context learning (ICL) capability
of LLMs is intriguing, and it is not yet fully understood how pretrained LLMs
acquire such capabilities. In this paper, we investigate the reason why a
transformer-based language model can accomplish in-context learning after
pre-training on a general language corpus by proposing one hypothesis that LLMs
can simulate kernel regression with internal representations when faced with
in-context examples. More concretely, we first prove that Bayesian inference on
in-context prompts can be asymptotically understood as kernel regression \\(\hat
y = \sum_i y_i K(x, x_i)/\sum_i K(x, x_i)\\) as the number of in-context
demonstrations grows. Then, we empirically investigate the in-context behaviors
of language models. We find that during ICL, the attention and hidden features
in LLMs match the behaviors of a kernel regression. Finally, our theory
provides insights into multiple phenomena observed in the ICL field: why
retrieving demonstrative samples similar to test samples can help, why ICL
performance is sensitive to the output formats, and why ICL accuracy benefits
from selecting in-distribution and representative samples.
