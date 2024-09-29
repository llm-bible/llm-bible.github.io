---
layout: publication
title: Domain45;specific Text Generation For Machine Translation
authors: Moslem Yasmin, Haque Rejwanul, Kelleher John D., Way Andy
conference: "Proceedings of the"
year: 2022
bibkey: moslem2022domain
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2208.05909"}
tags: ['Applications', 'Fine Tuning', 'Language Modeling', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Transformer']
---
Preservation of domain knowledge from the source to target is crucial in any translation workflow. It is common in the translation industry to receive highly specialized projects where there is hardly any parallel in45;domain data. In such scenarios where there is insufficient in45;domain data to fine45;tune Machine Translation (MT) models producing translations that are consistent with the relevant context is challenging. In this work we propose a novel approach to domain adaptation leveraging state45;of45;the45;art pretrained language models (LMs) for domain45;specific data augmentation for MT simulating the domain characteristics of either (a) a small bilingual dataset or (b) the monolingual source text to be translated. Combining this idea with back45;translation we can generate huge amounts of synthetic bilingual in45;domain data for both use cases. For our investigation we use the state45;of45;the45;art Transformer architecture. We employ mixed fine45;tuning to train models that significantly improve translation of in45;domain texts. More specifically in both scenarios our proposed methods achieve improvements of approximately 545;6 BLEU and 245;3 BLEU respectively on the Arabic45;to45;English and English45;to45;Arabic language pairs. Furthermore the outcome of human evaluation corroborates the automatic evaluation results.
