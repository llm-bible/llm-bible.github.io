---
layout: publication
title: Mucot: Multilingual Contrastive Training For Question-answering In Low-resource Languages
authors: Kumar Gokul Karthik, Gehlot Abhishek Singh, Mullappilly Sahal Shaji, Nandakumar Karthik
conference: "Arxiv"
year: 2022
bibkey: kumar2022multilingual
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2204.05814"}
  - {name: "Code", url: "https://github.com/gokulkarthik/mucot"}
tags: ['Applications', 'BERT', 'Fine Tuning', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'Training Techniques', 'Transformer']
---
Accuracy of English-language Question Answering (QA) systems has improved significantly in recent years with the advent of Transformer-based models (e.g. BERT). These models are pre-trained in a self-supervised fashion with a large English text corpus and further fine-tuned with a massive English QA dataset (e.g. SQuAD). However QA datasets on such a scale are not available for most of the other languages. Multi-lingual BERT-based models (mBERT) are often used to transfer knowledge from high-resource languages to low-resource languages. Since these models are pre-trained with huge text corpora containing multiple languages they typically learn language-agnostic embeddings for tokens from different languages. However directly training an mBERT-based QA system for low-resource languages is challenging due to the paucity of training data. In this work we augment the QA samples of the target language using translation and transliteration into other languages and use the augmented data to fine-tune an mBERT-based QA model which is already pre-trained in English. Experiments on the Google ChAII dataset show that fine-tuning the mBERT model with translations from the same language family boosts the question-answering performance whereas the performance degrades in the case of cross-language families. We further show that introducing a contrastive loss between the translated question-context feature pairs during the fine-tuning process prevents such degradation with cross-lingual family translations and leads to marginal improvement. The code for this work is available at https://github.com/gokulkarthik/mucot."
