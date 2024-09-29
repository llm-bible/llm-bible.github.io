---
layout: publication
title: Predicting Target Language CCG Supertags Improves Neural Machine Translation
authors: Nadejde Maria, Reddy Siva, Sennrich Rico, Dwojak Tomasz, Junczys-dowmunt Marcin, Koehn Philipp, Birch Alexandra
conference: "Arxiv"
year: 2017
bibkey: nadejde2017predicting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1702.01147"}
tags: ['Applications', 'Reinforcement Learning', 'Training Techniques']
---
Neural machine translation (NMT) models are able to partially learn syntactic information from sequential lexical information. Still some complex syntactic phenomena such as prepositional phrase attachment are poorly modeled. This work aims to answer two questions 1) Does explicitly modeling target language syntax help NMT 2) Is tight integration of words and syntax better than multitask training We introduce syntactic information in the form of CCG supertags in the decoder by interleaving the target supertags with the word sequence. Our results on WMT data show that explicitly modeling target45;syntax improves machine translation quality for German45;English a high45;resource pair and for Romanian45;English a low45;resource pair and also several syntactic phenomena including prepositional phrase attachment. Furthermore a tight coupling of words and syntax improves translation quality more than multitask training. By combining target45;syntax with adding source45;side dependency labels in the embedding layer we obtain a total improvement of 0.9 BLEU for German45;English and 1.2 BLEU for Romanian45;English.
