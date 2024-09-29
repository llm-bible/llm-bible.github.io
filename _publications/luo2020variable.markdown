---
layout: publication
title: VECO Variable And Flexible Cross45;lingual Pre45;training For Language Understanding And Generation
authors: Luo Fuli, Wang Wei, Liu Jiahao, Liu Yijia, Bi Bin, Huang Songfang, Huang Fei, Si Luo
conference: "Arxiv"
year: 2020
bibkey: luo2020variable
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2010.16046"}
tags: ['Applications', 'Attention Mechanism', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Training Techniques', 'Transformer']
---
Existing work in multilingual pretraining has demonstrated the potential of cross45;lingual transferability by training a unified Transformer encoder for multiple languages. However much of this work only relies on the shared vocabulary and bilingual contexts to encourage the correlation across languages which is loose and implicit for aligning the contextual representations between languages. In this paper we plug a cross45;attention module into the Transformer encoder to explicitly build the interdependence between languages. It can effectively avoid the degeneration of predicting masked words only conditioned on the context in its own language. More importantly when fine45;tuning on downstream tasks the cross45;attention module can be plugged in or out on45;demand thus naturally benefiting a wider range of cross45;lingual tasks from language understanding to generation. As a result the proposed cross45;lingual model delivers new state45;of45;the45;art results on various cross45;lingual understanding tasks of the XTREME benchmark covering text classification sequence labeling question answering and sentence retrieval. For cross45;lingual generation tasks it also outperforms all existing cross45;lingual models and state45;of45;the45;art Transformer variants on WMT14 English45;to45;German and English45;to45;French translation datasets with gains of up to 1~2 BLEU.
