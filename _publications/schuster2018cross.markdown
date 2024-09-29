---
layout: publication
title: Cross45;lingual Transfer Learning For Multilingual Task Oriented Dialog
authors: Schuster Sebastian, Gupta Sonal, Shah Rushin, Lewis Mike
conference: "Arxiv"
year: 2018
bibkey: schuster2018cross
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1810.13327"}
tags: ['Applications', 'Fine Tuning', 'Training Techniques']
---
One of the first steps in the utterance interpretation pipeline of many task45;oriented conversational AI systems is to identify user intents and the corresponding slots. Since data collection for machine learning models for this task is time45;consuming it is desirable to make use of existing data in a high45;resource language to train models in low45;resource languages. However development of such models has largely been hindered by the lack of multilingual training data. In this paper we present a new data set of 57k annotated utterances in English (43k) Spanish (8.6k) and Thai (5k) across the domains weather alarm and reminder. We use this data set to evaluate three different cross45;lingual transfer methods (1) translating the training data (2) using cross45;lingual pre45;trained embeddings and (3) a novel method of using a multilingual machine translation encoder as contextual word representations. We find that given several hundred training examples in the the target language the latter two methods outperform translating the training data. Further in very low45;resource settings multilingual contextual word representations give better results than using cross45;lingual static embeddings. We also compare the cross45;lingual methods to using monolingual resources in the form of contextual ELMo representations and find that given just small amounts of target language data this method outperforms all cross45;lingual methods which highlights the need for more sophisticated cross45;lingual methods.
