---
layout: publication
title: Fine45;tuning CLIP Text Encoders With Two45;step Paraphrasing
authors: Kim Hyunjae, Yoon Seunghyun, Bui Trung, Zhao Handong, Tran Quan, Dernoncourt Franck, Kang Jaewoo
conference: "Arxiv"
year: 2024
bibkey: kim2024fine
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.15120"}
tags: ['Applications', 'Pretraining Methods', 'RAG', 'Reinforcement Learning', 'Training Techniques']
---
Contrastive language45;image pre45;training (CLIP) models have demonstrated considerable success across various vision45;language tasks such as text45;to45;image retrieval where the model is required to effectively process natural language input to produce an accurate visual output. However current models still face limitations in dealing with linguistic variations in input queries such as paraphrases making it challenging to handle a broad range of user queries in real45;world applications. In this study we introduce a straightforward fine45;tuning approach to enhance the representations of CLIP models for paraphrases. Our approach involves a two45;step paraphrase generation process where we automatically create two categories of paraphrases from web45;scale image captions by leveraging large language models. Subsequently we fine45;tune the CLIP text encoder using these generated paraphrases while freezing the image encoder. Our resulting model which we call ParaCLIP exhibits significant improvements over baseline CLIP models across various tasks including paraphrased retrieval (with rank similarity scores improved by up to 2.037; and 5.637;) Visual Genome Relation and Attribution as well as seven semantic textual similarity tasks.
