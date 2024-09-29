---
layout: publication
title: Sequence45;to45;sequence Pre45;training With Data Augmentation For Sentence Rewriting
authors: Zhang Yi, Ge Tao, Wei Furu, Zhou Ming, Sun Xu
conference: "Arxiv"
year: 2019
bibkey: zhang2019sequence
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1909.06002"}
tags: ['Pretraining Methods', 'Training Techniques']
---
We study sequence45;to45;sequence (seq2seq) pre45;training with data augmentation for sentence rewriting. Instead of training a seq2seq model with gold training data and augmented data simultaneously we separate them to train in different phases pre45;training with the augmented data and fine45;tuning with the gold data. We also introduce multiple data augmentation methods to help model pre45;training for sentence rewriting. We evaluate our approach in two typical well45;defined sentence rewriting tasks Grammatical Error Correction (GEC) and Formality Style Transfer (FST). Experiments demonstrate our approach can better utilize augmented data without hurting the models trust in gold data and further improve the models performance with our proposed data augmentation methods. Our approach substantially advances the state45;of45;the45;art results in well45;recognized sentence rewriting benchmarks over both GEC and FST. Specifically it pushes the CoNLL45;2014 benchmarks F95;123;0.5125; score and JFLEG Test GLEU score to 62.61 and 63.54 in the restricted training setting 66.77 and 65.22 respectively in the unrestricted setting and advances GYAFC benchmarks BLEU to 74.24 (2.23 absolute improvement) in Eamp;M domain and 77.97 (2.64 absolute improvement) in Famp;R domain.
