---
layout: publication
title: Distilbert A Distilled Version Of BERT Smaller Faster Cheaper And Lighter
authors: Sanh Victor, Debut Lysandre, Chaumond Julien, Wolf Thomas
conference: "Arxiv"
year: 2019
bibkey: sanh2019distilled
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1910.01108"}
tags: ['BERT', 'Distillation', 'Efficiency And Optimization', 'Ethics And Bias', 'Fine Tuning', 'Language Modeling', 'Model Architecture', 'RAG', 'Training Techniques']
---
As Transfer Learning from large45;scale pre45;trained models becomes more prevalent in Natural Language Processing (NLP) operating these large models in on45;the45;edge and/or under constrained computational training or inference budgets remains challenging. In this work we propose a method to pre45;train a smaller general45;purpose language representation model called DistilBERT which can then be fine45;tuned with good performances on a wide range of tasks like its larger counterparts. While most prior work investigated the use of distillation for building task45;specific models we leverage knowledge distillation during the pre45;training phase and show that it is possible to reduce the size of a BERT model by 4037; while retaining 9737; of its language understanding capabilities and being 6037; faster. To leverage the inductive biases learned by larger models during pre45;training we introduce a triple loss combining language modeling distillation and cosine45;distance losses. Our smaller faster and lighter model is cheaper to pre45;train and we demonstrate its capabilities for on45;device computations in a proof45;of45;concept experiment and a comparative on45;device study.
