---
layout: publication
title: PERFECT Prompt45;free And Efficient Few45;shot Learning With Language Models
authors: Mahabadi Rabeeh Karimi, Zettlemoyer Luke, Henderson James, Saeidi Marzieh, Mathias Lambert, Stoyanov Veselin, Yazdani Majid
conference: "Arxiv"
year: 2022
bibkey: mahabadi2022prompt
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2204.01172"}
  - {name: "Code", url: "https://github.com/facebookresearch/perfect.git"}
tags: ['BERT', 'Has Code', 'Masked Language Model', 'Pretraining Methods', 'Prompting', 'RAG', 'Reinforcement Learning', 'Training Techniques']
---
Current methods for few45;shot fine45;tuning of pretrained masked language models (PLMs) require carefully engineered prompts and verbalizers for each new task to convert examples into a cloze45;format that the PLM can score. In this work we propose PERFECT a simple and efficient method for few45;shot fine45;tuning of PLMs without relying on any such handcrafting which is highly effective given as few as 32 data points. PERFECT makes two key design choices First we show that manually engineered task prompts can be replaced with task45;specific adapters that enable sample45;efficient fine45;tuning and reduce memory and storage costs by roughly factors of 5 and 100 respectively. Second instead of using handcrafted verbalizers we learn new multi45;token label embeddings during fine45;tuning which are not tied to the model vocabulary and which allow us to avoid complex auto45;regressive decoding. These embeddings are not only learnable from limited data but also enable nearly 100x faster training and inference. Experiments on a wide range of few45;shot NLP tasks demonstrate that PERFECT while being simple and efficient also outperforms existing state45;of45;the45;art few45;shot learning methods. Our code is publicly available at https://github.com/facebookresearch/perfect.git.
