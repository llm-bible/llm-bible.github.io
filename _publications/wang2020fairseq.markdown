---
layout: publication
title: 'Fairseq S2T: Fast Speech-to-text Modeling With Fairseq'
authors: Changhan Wang et al.
conference: Arxiv
year: 2020
citations: 20
bibkey: wang2020fairseq
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2010.05171'}, {name: Code,
    url: 'https://github.com/pytorch/fairseq/tree/master/examples/speech_to_text'}]
tags: [Transformer, Fine-Tuning]
---
We introduce fairseq S2T, a fairseq extension for speech-to-text (S2T)
modeling tasks such as end-to-end speech recognition and speech-to-text
translation. It follows fairseq's careful design for scalability and
extensibility. We provide end-to-end workflows from data pre-processing, model
training to offline (online) inference. We implement state-of-the-art
RNN-based, Transformer-based as well as Conformer-based models and open-source
detailed training recipes. Fairseq's machine translation models and language
models can be seamlessly integrated into S2T workflows for multi-task learning
or transfer learning. Fairseq S2T documentation and examples are available at
https://github.com/pytorch/fairseq/tree/master/examples/speech_to_text.