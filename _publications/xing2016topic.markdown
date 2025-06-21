---
layout: publication
title: Topic Aware Neural Response Generation
authors: Chen Xing et al.
conference: Arxiv
year: 2016
citations: 117
bibkey: xing2016topic
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1606.08340'}]
tags: [Transformer, RAG, Ethics and Bias]
---
We consider incorporating topic information into the sequence-to-sequence
framework to generate informative and interesting responses for chatbots. To
this end, we propose a topic aware sequence-to-sequence (TA-Seq2Seq) model. The
model utilizes topics to simulate prior knowledge of human that guides them to
form informative and interesting responses in conversation, and leverages the
topic information in generation by a joint attention mechanism and a biased
generation probability. The joint attention mechanism summarizes the hidden
vectors of an input message as context vectors by message attention,
synthesizes topic vectors by topic attention from the topic words of the
message obtained from a pre-trained LDA model, and let these vectors jointly
affect the generation of words in decoding. To increase the possibility of
topic words appearing in responses, the model modifies the generation
probability of topic words by adding an extra probability item to bias the
overall distribution. Empirical study on both automatic evaluation metrics and
human annotations shows that TA-Seq2Seq can generate more informative and
interesting responses, and significantly outperform the-state-of-the-art
response generation models.