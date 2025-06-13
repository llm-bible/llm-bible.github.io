---
layout: publication
title: 'Your Large Language Models Are Leaving Fingerprints'
authors: Hope Mcgovern, Rickard Stureborg, Yoshi Suhara, Dimitris Alikaniotis
conference: "Arxiv"
year: 2024
bibkey: mcgovern2024your
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.14057"}
tags: ['Arxiv', 'Training Techniques', 'Model Architecture', 'Pretraining Methods', 'Transformer']
---
It has been shown that finetuned transformers and other supervised detectors
effectively distinguish between human and machine-generated text in some
situations arXiv:2305.13242, but we find that even simple classifiers on top of
n-gram and part-of-speech features can achieve very robust performance on both
in- and out-of-domain data. To understand how this is possible, we analyze
machine-generated output text in five datasets, finding that LLMs possess
unique fingerprints that manifest as slight differences in the frequency of
certain lexical and morphosyntactic features. We show how to visualize such
fingerprints, describe how they can be used to detect machine-generated text
and find that they are even robust across textual domains. We find that
fingerprints are often persistent across models in the same model family (e.g.
llama-13b vs. llama-65b) and that models fine-tuned for chat are easier to
detect than standard language models, indicating that LLM fingerprints may be
directly induced by the training data.
