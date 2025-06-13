---
layout: publication
title: 'Toward Improving Coherence And Diversity Of Slogan Generation'
authors: Yiping Jin, Akshay Bhatia, Dittaya Wanvarie, Phu T. V. Le
conference: "Arxiv"
year: 2021
bibkey: jin2021toward
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2102.05924"}
tags: ['Pretraining Methods', 'Training Techniques', 'Transformer', 'Model Architecture']
---
Previous work in slogan generation focused on utilising slogan skeletons
mined from existing slogans. While some generated slogans can be catchy, they
are often not coherent with the company's focus or style across their marketing
communications because the skeletons are mined from other companies' slogans.
We propose a sequence-to-sequence (seq2seq) transformer model to generate
slogans from a brief company description. A naive seq2seq model fine-tuned for
slogan generation is prone to introducing false information. We use company
name delexicalisation and entity masking to alleviate this problem and improve
the generated slogans' quality and truthfulness. Furthermore, we apply
conditional training based on the first words' POS tag to generate
syntactically diverse slogans. Our best model achieved a ROUGE-1/-2/-L F1 score
of 35.58/18.47/33.32. Besides, automatic and human evaluations indicate that
our method generates significantly more factual, diverse and catchy slogans
than strong LSTM and transformer seq2seq baselines.
