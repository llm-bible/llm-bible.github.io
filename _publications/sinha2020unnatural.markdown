---
layout: publication
title: Unnatural Language Inference
authors: Sinha Koustuv, Parthasarathi Prasanna, Pineau Joelle, Williams Adina
conference: "Arxiv"
year: 2020
bibkey: sinha2020unnatural
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2101.00010"}
  - {name: "Code", url: "https://github.com/facebookresearch/unlu"}
tags: ['Applications', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'Transformer']
---
Recent investigations into the inner45;workings of state45;of45;the45;art large45;scale pre45;trained Transformer45;based Natural Language Understanding (NLU) models indicate that they appear to know humanlike syntax at least to some extent. We provide novel evidence that complicates this claim we find that state45;of45;the45;art Natural Language Inference (NLI) models assign the same labels to permuted examples as they do to the original i.e. they are largely invariant to random word45;order permutations. This behavior notably differs from that of humans; we struggle with ungrammatical sentences. To measure the severity of this issue we propose a suite of metrics and investigate which properties of particular permutations lead models to be word45;order invariant. In the MNLI dataset for example we find almost all (98.737;) examples contain at least one permutation which elicits the gold label. Models are sometimes even able to assign gold labels to permutations that they originally failed to predict correctly. We provide a comprehensive empirical evaluation of this phenomenon and further show that this issue exists for both Transformers and pre45;Transformer RNN / ConvNet based encoders as well as across multiple languages (English and Mandarin Chinese). Our code and data are available at https://github.com/facebookresearch/unlu.
