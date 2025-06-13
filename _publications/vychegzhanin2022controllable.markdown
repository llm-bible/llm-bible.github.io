---
layout: publication
title: 'Collocation2text: Controllable Text Generation From Guide Phrases In Russian'
authors: Sergey Vychegzhanin, Evgeny Kotelnikov
conference: "Arxiv"
year: 2022
bibkey: vychegzhanin2022controllable
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2206.09248"}
tags: ['Fine-Tuning', 'GPT', 'Applications', 'Language Modeling', 'Model Architecture', 'Training Techniques', 'Pretraining Methods', 'BERT', 'Prompting']
---
Large pre-trained language models are capable of generating varied and fluent
texts. Starting from the prompt, these models generate a narrative that can
develop unpredictably. The existing methods of controllable text generation,
which guide the narrative in the text in the user-specified direction, require
creating a training corpus and an additional time-consuming training procedure.
The paper proposes and investigates Collocation2Text, a plug-and-play method
for automatic controllable text generation in Russian, which does not require
fine-tuning. The method is based on two interacting models: the autoregressive
language ruGPT-3 model and the autoencoding language ruRoBERTa model. The idea
of the method is to shift the output distribution of the autoregressive model
according to the output distribution of the autoencoding model in order to
ensure a coherent transition of the narrative in the text towards the guide
phrase, which can contain single words or collocations. The autoencoding model,
which is able to take into account the left and right contexts of the token,
"tells" the autoregressive model which tokens are the most and least logical at
the current generation step, increasing or decreasing the probabilities of the
corresponding tokens. The experiments on generating news articles using the
proposed method showed its effectiveness for automatically generated fluent
texts which contain coherent transitions between user-specified phrases.
