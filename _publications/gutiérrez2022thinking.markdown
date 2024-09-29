---
layout: publication
title: Thinking About GPT45;3 In45;context Learning For Biomedical IE Think Again
authors: Gutiérrez Bernal Jiménez, Mcneal Nikolas, Washington Clay, Chen You, Li Lang, Sun Huan, Su Yu
conference: "Arxiv"
year: 2022
bibkey: gutiérrez2022thinking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2203.08410"}
tags: ['BERT', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Survey Paper', 'Training Techniques']
---
The strong few45;shot in45;context learning capability of large pre45;trained language models (PLMs) such as GPT45;3 is highly appealing for application domains such as biomedicine which feature high and diverse demands of language technologies but also high data annotation costs. In this paper we present the first systematic and comprehensive study to compare the few45;shot performance of GPT45;3 in45;context learning with fine45;tuning smaller (i.e. BERT45;sized) PLMs on two highly representative biomedical information extraction tasks named entity recognition and relation extraction. We follow the true few45;shot setting to avoid overestimating models few45;shot performance by model selection over a large validation set. We also optimize GPT45;3s performance with known techniques such as contextual calibration and dynamic in45;context example retrieval. However our results show that GPT45;3 still significantly underperforms compared to simply fine45;tuning a smaller PLM. In addition GPT45;3 in45;context learning also yields smaller gains in accuracy when more training data becomes available. Our in45;depth analyses further reveal issues of the in45;context learning setting that may be detrimental to information extraction tasks in general. Given the high cost of experimenting with GPT45;3 we hope our study provides guidance for biomedical researchers and practitioners towards more promising directions such as fine45;tuning small PLMs.
