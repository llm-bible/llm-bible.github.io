---
layout: publication
title: Mogrifier LSTM
authors: Melis Gábor, Kočiský Tomáš, Blunsom Phil
conference: "Arxiv"
year: 2019
bibkey: melis2019mogrifier
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1909.01792"}
tags: ['Model Architecture', 'Pretraining Methods', 'Transformer']
---
Many advances in Natural Language Processing have been based upon more expressive models for how inputs interact with the context in which they occur. Recurrent networks which have enjoyed a modicum of success still lack the generalization and systematicity ultimately required for modelling language. In this work we propose an extension to the venerable Long Short45;Term Memory in the form of mutual gating of the current input and the previous output. This mechanism affords the modelling of a richer space of interactions between inputs and their context. Equivalently our model can be viewed as making the transition function given by the LSTM context45;dependent. Experiments demonstrate markedly improved generalization on language modelling in the range of 345;4 perplexity points on Penn Treebank and Wikitext45;2 and 0.0145;0.05 bpc on four character45;based datasets. We establish a new state of the art on all datasets with the exception of Enwik8 where we close a large gap between the LSTM and Transformer models.
