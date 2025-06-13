---
layout: publication
title: 'Leveraging Pre-trained Checkpoints For Sequence Generation Tasks'
authors: Sascha Rothe, Shashi Narayan, Aliaksei Severyn
conference: "Arxiv"
year: 2019
bibkey: rothe2019leveraging
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/1907.12461'}
tags: ['Transformer', 'RAG', 'Training Techniques', 'BERT', 'Model Architecture', 'GPT', 'Merging', 'Applications', 'Pre-Training', 'Pretraining Methods']
---
Unsupervised pre-training of large neural models has recently revolutionized
Natural Language Processing. By warm-starting from the publicly released
checkpoints, NLP practitioners have pushed the state-of-the-art on multiple
benchmarks while saving significant amounts of compute time. So far the focus
has been mainly on the Natural Language Understanding tasks. In this paper, we
demonstrate the efficacy of pre-trained checkpoints for Sequence Generation. We
developed a Transformer-based sequence-to-sequence model that is compatible
with publicly available pre-trained BERT, GPT-2 and RoBERTa checkpoints and
conducted an extensive empirical study on the utility of initializing our
model, both encoder and decoder, with these checkpoints. Our models result in
new state-of-the-art results on Machine Translation, Text Summarization,
Sentence Splitting, and Sentence Fusion.
