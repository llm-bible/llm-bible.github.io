---
layout: publication
title: 'Asymptotic Theory Of In-context Learning By Linear Attention'
authors: Yue M. Lu, Mary I. Letey, Jacob A. Zavatone-veth, Anindita Maiti, Cengiz Pehlevan
conference: "Arxiv"
year: 2024
bibkey: lu2024asymptotic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.11751"}
tags: ['Transformer', 'Model Architecture', 'Training Techniques', 'Attention Mechanism', 'Pretraining Methods', 'Prompting', 'In-Context Learning']
---
Transformers have a remarkable ability to learn and execute tasks based on
examples provided within the input itself, without explicit prior training. It
has been argued that this capability, known as in-context learning (ICL), is a
cornerstone of Transformers' success, yet questions about the necessary sample
complexity, pretraining task diversity, and context length for successful ICL
remain unresolved. Here, we provide a precise answer to these questions in an
exactly solvable model of ICL of a linear regression task by linear attention.
We derive sharp asymptotics for the learning curve in a phenomenologically-rich
scaling regime where the token dimension is taken to infinity; the context
length and pretraining task diversity scale proportionally with the token
dimension; and the number of pretraining examples scales quadratically. We
demonstrate a double-descent learning curve with increasing pretraining
examples, and uncover a phase transition in the model's behavior between low
and high task diversity regimes: In the low diversity regime, the model tends
toward memorization of training tasks, whereas in the high diversity regime, it
achieves genuine in-context learning and generalization beyond the scope of
pretrained tasks. These theoretical insights are empirically validated through
experiments with both linear attention and full nonlinear Transformer
architectures.
