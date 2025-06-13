---
layout: publication
title: 'Taken Out Of Context: On Measuring Situational Awareness In Llms'
authors: Lukas Berglund, Asa Cooper Stickland, Mikita Balesni, Max Kaufmann, Meg Tong, Tomasz Korbak, Daniel Kokotajlo, Owain Evans
conference: "Arxiv"
year: 2023
bibkey: berglund2023taken
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.00667"}
  - {name: "Code", url: "https://github.com/AsaCooperStickland/situational-awareness-evals"}
tags: ['Responsible AI', 'GPT', 'Model Architecture', 'Training Techniques', 'Has Code', 'Scaling Laws', 'Prompting', 'In-Context Learning']
---
We aim to better understand the emergence of `situational awareness' in large
language models (LLMs). A model is situationally aware if it's aware that it's
a model and can recognize whether it's currently in testing or deployment.
Today's LLMs are tested for safety and alignment before they are deployed. An
LLM could exploit situational awareness to achieve a high score on safety
tests, while taking harmful actions after deployment. Situational awareness may
emerge unexpectedly as a byproduct of model scaling. One way to better foresee
this emergence is to run scaling experiments on abilities necessary for
situational awareness. As such an ability, we propose `out-of-context
reasoning' (in contrast to in-context learning). We study out-of-context
reasoning experimentally. First, we finetune an LLM on a description of a test
while providing no examples or demonstrations. At test time, we assess whether
the model can pass the test. To our surprise, we find that LLMs succeed on this
out-of-context reasoning task. Their success is sensitive to the training setup
and only works when we apply data augmentation. For both GPT-3 and LLaMA-1,
performance improves with model size. These findings offer a foundation for
further empirical study, towards predicting and potentially controlling the
emergence of situational awareness in LLMs. Code is available at:
https://github.com/AsaCooperStickland/situational-awareness-evals.
