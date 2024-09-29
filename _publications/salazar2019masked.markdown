---
layout: publication
title: Masked Language Model Scoring
authors: Salazar Julian, Liang Davis, Nguyen Toan Q., Kirchhoff Katrin
conference: "Proceedings of the"
year: 2019
bibkey: salazar2019masked
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1910.14659"}
  - {name: "Code", url: "https://github.com/awslabs/mlm&#45;scoring"}
tags: ['BERT', 'Ethics And Bias', 'Fine Tuning', 'GPT', 'Has Code', 'Masked Language Model', 'Model Architecture', 'Pretraining Methods', 'Tools']
---
Pretrained masked language models (MLMs) require finetuning for most NLP tasks. Instead we evaluate MLMs out of the box via their pseudo45;log45;likelihood scores (PLLs) which are computed by masking tokens one by one. We show that PLLs outperform scores from autoregressive language models like GPT45;2 in a variety of tasks. By rescoring ASR and NMT hypotheses RoBERTa reduces an end45;to45;end LibriSpeech models WER by 3037; relative and adds up to +1.7 BLEU on state45;of45;the45;art baselines for low45;resource translation pairs with further gains from domain adaptation. We attribute this success to PLLs unsupervised expression of linguistic acceptability without a left45;to45;right bias greatly improving on scores from GPT45;2 (+10 points on island effects NPI licensing in BLiMP). One can finetune MLMs to give scores without masking enabling computation in a single inference pass. In all PLLs and their associated pseudo45;perplexities (PPPLs) enable plug45;and45;play use of the growing number of pretrained MLMs; e.g. we use a single cross45;lingual model to rescore translations in multiple languages. We release our library for language model scoring at https://github.com/awslabs/mlm&#45;scoring.
