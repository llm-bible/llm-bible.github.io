---
layout: publication
title: 'Sequence-to-sequence Pre-training With Data Augmentation For Sentence Rewriting'
authors: Zhang Yi, Ge Tao, Wei Furu, Zhou Ming, Sun Xu
conference: "Arxiv"
year: 2019
bibkey: zhang2019sequence
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1909.06002"}
tags: ['Fine Tuning', 'Pretraining Methods', 'Training Techniques']
---
"We study sequence-to-sequence (seq2seq) pre-training with data augmentation for sentence rewriting. Instead of training a seq2seq model with gold training data and augmented data simultaneously, we separate them to train in different phases: pre-training with the augmented data and fine-tuning with the gold data. We also introduce multiple data augmentation methods to help model pre-training for sentence rewriting. We evaluate our approach in two typical well-defined sentence rewriting tasks: Grammatical Error Correction (GEC) and Formality Style Transfer (FST). Experiments demonstrate our approach can better utilize augmented data without hurting the model's trust in gold data and further improve the model's performance with our proposed data augmentation methods. Our approach substantially advances the state-of-the-art results in well-recognized sentence rewriting benchmarks over both GEC and FST. Specifically, it pushes the CoNLL-2014 benchmark's \(F_{0.5}\) score and JFLEG Test GLEU score to 62.61 and 63.54 in the restricted training setting, 66.77 and 65.22 respectively in the unrestricted setting, and advances GYAFC benchmark's BLEU to 74.24 (2.23 absolute improvement) in E&amp;M domain and 77.97 (2.64 absolute improvement) in F&amp;R domain."
