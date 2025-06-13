---
layout: publication
title: 'Vector Representations Of Idioms In Conversational Systems'
authors: Tosin Adewumi, Foteini Liwicki, Marcus Liwicki
conference: "Arxiv"
year: 2022
bibkey: adewumi2022vector
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2205.03666"}
tags: ['Transformer', 'GPT', 'Applications', 'Model Architecture', 'Pretraining Methods', 'Prompting']
---
We demonstrate, in this study, that an open-domain conversational system
trained on idioms or figurative language generates more fitting responses to
prompts containing idioms. Idioms are part of everyday speech in many
languages, across many cultures, but they pose a great challenge for many
Natural Language Processing (NLP) systems that involve tasks such as
Information Retrieval (IR) and Machine Translation (MT), besides conversational
AI. We utilize the Potential Idiomatic Expression (PIE)-English idioms corpus
for the two tasks that we investigate: classification and conversation
generation. We achieve state-of-the-art (SoTA) result of 98% macro F1 score on
the classification task by using the SoTA T5 model. We experiment with three
instances of the SoTA dialogue model, Dialogue Generative Pre-trained
Transformer (DialoGPT), for conversation generation. Their performances are
evaluated using the automatic metric perplexity and human evaluation. The
results show that the model trained on the idiom corpus generates more fitting
responses to prompts containing idioms 71.9% of the time, compared to a similar
model not trained on the idioms corpus. We contribute the model checkpoint/demo
and code on the HuggingFace hub for public access.
