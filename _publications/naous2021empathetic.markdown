---
layout: publication
title: 'Empathetic BERT2BERT Conversational Model: Learning Arabic Language Generation With Little Data'
authors: Tarek Naous, Wissam Antoun, Reem A. Mahmoud, Hazem Hajj
conference: "Arxiv"
year: 2021
bibkey: naous2021empathetic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2103.04353"}
tags: ['Transformer', 'Agentic', 'Applications', 'RAG', 'Model Architecture', 'Pretraining Methods', 'BERT']
---
Enabling empathetic behavior in Arabic dialogue agents is an important aspect
of building human-like conversational models. While Arabic Natural Language
Processing has seen significant advances in Natural Language Understanding
(NLU) with language models such as AraBERT, Natural Language Generation (NLG)
remains a challenge. The shortcomings of NLG encoder-decoder models are
primarily due to the lack of Arabic datasets suitable to train NLG models such
as conversational agents. To overcome this issue, we propose a
transformer-based encoder-decoder initialized with AraBERT parameters. By
initializing the weights of the encoder and decoder with AraBERT pre-trained
weights, our model was able to leverage knowledge transfer and boost
performance in response generation. To enable empathy in our conversational
model, we train it using the ArabicEmpatheticDialogues dataset and achieve high
performance in empathetic response generation. Specifically, our model achieved
a low perplexity value of 17.0 and an increase in 5 BLEU points compared to the
previous state-of-the-art model. Also, our proposed model was rated highly by
85 human evaluators, validating its high capability in exhibiting empathy while
generating relevant and fluent responses in open-domain settings.
