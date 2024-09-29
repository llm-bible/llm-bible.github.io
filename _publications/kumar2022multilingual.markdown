---
layout: publication
title: Mucot Multilingual Contrastive Training For Question45;answering In Low45;resource Languages
authors: Kumar Gokul Karthik, Gehlot Abhishek Singh, Mullappilly Sahal Shaji, Nandakumar Karthik
conference: "Arxiv"
year: 2022
bibkey: kumar2022multilingual
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2204.05814"}
  - {name: "Code", url: "https://github.com/gokulkarthik/mucot"}
tags: ['Applications', 'BERT', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'Training Techniques', 'Transformer']
---
Accuracy of English45;language Question Answering (QA) systems has improved significantly in recent years with the advent of Transformer45;based models (e.g. BERT). These models are pre45;trained in a self45;supervised fashion with a large English text corpus and further fine45;tuned with a massive English QA dataset (e.g. SQuAD). However QA datasets on such a scale are not available for most of the other languages. Multi45;lingual BERT45;based models (mBERT) are often used to transfer knowledge from high45;resource languages to low45;resource languages. Since these models are pre45;trained with huge text corpora containing multiple languages they typically learn language45;agnostic embeddings for tokens from different languages. However directly training an mBERT45;based QA system for low45;resource languages is challenging due to the paucity of training data. In this work we augment the QA samples of the target language using translation and transliteration into other languages and use the augmented data to fine45;tune an mBERT45;based QA model which is already pre45;trained in English. Experiments on the Google ChAII dataset show that fine45;tuning the mBERT model with translations from the same language family boosts the question45;answering performance whereas the performance degrades in the case of cross45;language families. We further show that introducing a contrastive loss between the translated question45;context feature pairs during the fine45;tuning process prevents such degradation with cross45;lingual family translations and leads to marginal improvement. The code for this work is available at https://github.com/gokulkarthik/mucot.
