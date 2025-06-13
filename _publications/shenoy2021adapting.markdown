---
layout: publication
title: 'Adapting Long Context NLM For ASR Rescoring In Conversational Agents'
authors: Ashish Shenoy, Sravan Bodapati, Monica Sunkara, Srikanth Ronanki, Katrin Kirchhoff
conference: "Arxiv"
year: 2021
bibkey: shenoy2021adapting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2104.11070"}
tags: ['Masked Language Model', 'Agentic', 'Model Architecture', 'RAG', 'Merging', 'Pretraining Methods', 'BERT', 'Transformer', 'Attention Mechanism']
---
Neural Language Models (NLM), when trained and evaluated with context
spanning multiple utterances, have been shown to consistently outperform both
conventional n-gram language models and NLMs that use limited context. In this
paper, we investigate various techniques to incorporate turn based context
history into both recurrent (LSTM) and Transformer-XL based NLMs. For recurrent
based NLMs, we explore context carry over mechanism and feature based
augmentation, where we incorporate other forms of contextual information such
as bot response and system dialogue acts as classified by a Natural Language
Understanding (NLU) model. To mitigate the sharp nearby, fuzzy far away problem
with contextual NLM, we propose the use of attention layer over lexical
metadata to improve feature based augmentation. Additionally, we adapt our
contextual NLM towards user provided on-the-fly speech patterns by leveraging
encodings from a large pre-trained masked language model and performing fusion
with a Transformer-XL based NLM. We test our proposed models using N-best
rescoring of ASR hypotheses of task-oriented dialogues and also evaluate on
downstream NLU tasks such as intent classification and slot labeling. The best
performing model shows a relative WER between 1.6% and 9.1% and a slot labeling
F1 score improvement of 4% over non-contextual baselines.
