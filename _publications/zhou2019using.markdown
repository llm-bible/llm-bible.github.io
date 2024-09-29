---
layout: publication
title: Using Interlinear Glosses As Pivot In Low45;resource Multilingual Machine Translation
authors: Zhou Zhong, Levin Lori, Mortensen David R., Waibel Alex
conference: "Arxiv"
year: 2019
bibkey: zhou2019using
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1911.02709"}
tags: ['Applications', 'Attention Mechanism', 'Model Architecture', 'Reinforcement Learning']
---
We demonstrate a new approach to Neural Machine Translation (NMT) for low45;resource languages using a ubiquitous linguistic resource Interlinear Glossed Text (IGT). IGT represents a non45;English sentence as a sequence of English lemmas and morpheme labels. As such it can serve as a pivot or interlingua for NMT. Our contribution is four45;fold. Firstly we pool IGT for 1497 languages in ODIN (54545 glosses) and 70918 glosses in Arapaho and train a gloss45;to45;target NMT system from IGT to English with a BLEU score of 25.94. We introduce a multilingual NMT model that tags all glossed text with gloss45;source language tags and train a universal system with shared attention across 1497 languages. Secondly we use the IGT gloss45;to45;target translation as a key step in an English45;Turkish MT system trained on only 865 lines from ODIN. Thirdly we we present five metrics for evaluating extremely low45;resource translation when BLEU is no longer sufficient and evaluate the Turkish low45;resource system using BLEU and also using accuracy of matching nouns verbs agreement tense and spurious repetition showing large improvements.
