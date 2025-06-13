---
layout: publication
title: 'Bok: Introducing Bag-of-keywords Loss For Interpretable Dialogue Response Generation'
authors: Suvodip Dey, Maunendra Sankar Desarkar
conference: "Arxiv"
year: 2025
bibkey: dey2025introducing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.10328"}
tags: ['GPT', 'Applications', 'Interpretability and Explainability', 'RAG', 'Model Architecture', 'Language Modeling', 'Training Techniques']
---
The standard language modeling (LM) loss by itself has been shown to be
inadequate for effective dialogue modeling. As a result, various training
approaches, such as auxiliary loss functions and leveraging human feedback, are
being adopted to enrich open-domain dialogue systems. One such auxiliary loss
function is Bag-of-Words (BoW) loss, defined as the cross-entropy loss for
predicting all the words/tokens of the next utterance. In this work, we propose
a novel auxiliary loss named Bag-of-Keywords (BoK) loss to capture the central
thought of the response through keyword prediction and leverage it to enhance
the generation of meaningful and interpretable responses in open-domain
dialogue systems. BoK loss upgrades the BoW loss by predicting only the
keywords or critical words/tokens of the next utterance, intending to estimate
the core idea rather than the entire response. We incorporate BoK loss in both
encoder-decoder (T5) and decoder-only (DialoGPT) architecture and train the
models to minimize the weighted sum of BoK and LM (BoK-LM) loss. We perform our
experiments on two popular open-domain dialogue datasets, DailyDialog and
Persona-Chat. We show that the inclusion of BoK loss improves the dialogue
generation of backbone models while also enabling post-hoc interpretability. We
also study the effectiveness of BoK-LM loss as a reference-free metric and
observe comparable performance to the state-of-the-art metrics on various
dialogue evaluation datasets.
