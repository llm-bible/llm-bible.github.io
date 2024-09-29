---
layout: publication
title: Microsoft Translator At WMT 2019 Towards Large45;scale Document45;level Neural Machine Translation
authors: Junczys-dowmunt Marcin
conference: "Arxiv"
year: 2019
bibkey: junczysdowmunt2019microsoft
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1907.06170"}
tags: ['Applications', 'BERT', 'Model Architecture', 'Pretraining Methods', 'Training Techniques', 'Transformer']
---
This paper describes the Microsoft Translator submissions to the WMT19 news translation shared task for English45;German. Our main focus is document45;level neural machine translation with deep transformer models. We start with strong sentence45;level baselines trained on large45;scale data created via data45;filtering and noisy back45;translation and find that back45;translation seems to mainly help with translationese input. We explore fine45;tuning techniques deeper models and different ensembling strategies to counter these effects. Using document boundaries present in the authentic and synthetic parallel data we create sequences of up to 1000 subword segments and train transformer translation models. We experiment with data augmentation techniques for the smaller authentic data with document45;boundaries and for larger authentic data without boundaries. We further explore multi45;task training for the incorporation of document45;level source language monolingual data via the BERT45;objective on the encoder and two45;pass decoding for combinations of sentence45;level and document45;level systems. Based on preliminary human evaluation results evaluators strongly prefer the document45;level systems over our comparable sentence45;level system. The document45;level systems also seem to score higher than the human references in source45;based direct assessment.
