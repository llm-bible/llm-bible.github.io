---
layout: publication
title: 'Sequence-to-sequence Spanish Pre-trained Language Models'
authors: Araujo Vladimir, Trusca Maria Mihaela, Tufiño Rodrigo, Moens Marie-francine
conference: "Arxiv"
year: 2023
bibkey: araujo2023sequence
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.11259"}
  - {name: "Code", url: "https://github.com/vgaraujov/Seq2Seq-Spanish-PLMs"}
tags: ['Applications', 'BERT', 'Fine Tuning', 'GPT', 'Has Code', 'Merging', 'Model Architecture']
---
In recent years, significant advancements in pre-trained language models have driven the creation of numerous non-English language variants, with a particular emphasis on encoder-only and decoder-only architectures. While Spanish language models based on BERT and GPT have demonstrated proficiency in natural language understanding and generation, there remains a noticeable scarcity of encoder-decoder models explicitly designed for sequence-to-sequence tasks, which aim to map input sequences to generate output sequences conditionally. This paper breaks new ground by introducing the implementation and evaluation of renowned encoder-decoder architectures exclusively pre-trained on Spanish corpora. Specifically, we present Spanish versions of BART, T5, and BERT2BERT-style models and subject them to a comprehensive assessment across various sequence-to-sequence tasks, including summarization, question answering, split-and-rephrase, dialogue, and translation. Our findings underscore the competitive performance of all models, with the BART- and T5-based models emerging as top performers across all tasks. We have made all models publicly available to the research community to foster future explorations and advancements in Spanish NLP: https://github.com/vgaraujov/Seq2Seq-Spanish-PLMs.
