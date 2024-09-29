---
layout: publication
title: Large Pre-trained Language Models Contain Human-like Biases of What is Right and Wrong to Do
authors: Schramowski Patrick, Turan Cigdem, Andersen Nico, Rothkopf Constantin A., Kersting Kristian
conference: "Arxiv"
year: 2021
bibkey: schramowski2021large
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2103.11790"}
tags: ['BERT', 'Ethics And Bias', 'Fine Tuning', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Training Techniques', 'Transformer']
---
Artificial writing is permeating our lives due to recent advances in large-scale transformer-based language models (LMs) such as BERT its variants GPT-2/3 and others. Using them as pre-trained models and fine-tuning them for specific tasks researchers have extended state of the art for many NLP tasks and shown that they capture not only linguistic knowledge but also retain general knowledge implicitly present in the data. Unfortunately LMs trained on unfiltered text corpora suffer from degenerated and biased behaviour. While this is well established we show that recent LMs also contain human-like biases of what is right and wrong to do some form of ethical and moral norms of the society -- they bring a moral direction to surface. That is we show that these norms can be captured geometrically by a direction which can be computed e.g. by a PCA in the embedding space reflecting well the agreement of phrases to social norms implicitly expressed in the training texts and providing a path for attenuating or even preventing toxic degeneration in LMs. Being able to rate the (non-)normativity of arbitrary phrases without explicitly training the LM for this task we demonstrate the capabilities of the moral direction for guiding (even other) LMs towards producing normative text and showcase it on RealToxicityPrompts testbed preventing the neural toxic degeneration in GPT-2.
