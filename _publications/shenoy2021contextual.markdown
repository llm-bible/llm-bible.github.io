---
layout: publication
title: 'Contextual Biasing Of Language Models For Speech Recognition In Goal-oriented Conversational Agents'
authors: Shenoy Ashish, Bodapati Sravan, Kirchhoff Katrin
conference: "Arxiv"
year: 2021
bibkey: shenoy2021contextual
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2103.10325"}
tags: ['Agentic', 'Applications', 'BERT', 'Ethics And Bias', 'Model Architecture']
---
Goal-oriented conversational interfaces are designed to accomplish specific tasks and typically have interactions that tend to span multiple turns adhering to a pre-defined structure and a goal. However, conventional neural language models (NLM) in Automatic Speech Recognition (ASR) systems are mostly trained sentence-wise with limited context. In this paper, we explore different ways to incorporate context into a LSTM based NLM in order to model long range dependencies and improve speech recognition. Specifically, we use context carry over across multiple turns and use lexical contextual cues such as system dialog act from Natural Language Understanding (NLU) models and the user provided structure of the chatbot. We also propose a new architecture that utilizes context embeddings derived from BERT on sample utterances provided during inference time. Our experiments show a word error rate (WER) relative reduction of 7&#37; over non-contextual utterance-level NLM rescorers on goal-oriented audio datasets.
