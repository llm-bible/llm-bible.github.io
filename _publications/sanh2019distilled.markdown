---
layout: publication
title: "Distilbert, A Distilled Version Of BERT: Smaller, Faster, Cheaper And Lighter"
authors: Sanh Victor, Debut Lysandre, Chaumond Julien, Wolf Thomas
conference: "Arxiv"
year: 2019
bibkey: sanh2019distilled
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1910.01108"}
tags: ['BERT', 'Distillation', 'Efficiency And Optimization', 'Ethics And Bias', 'Fine Tuning', 'Language Modeling', 'Model Architecture', 'RAG', 'Training Techniques']
---
As Transfer Learning from large-scale pre-trained models becomes more prevalent in Natural Language Processing (NLP) operating these large models in on-the-edge and/or under constrained computational training or inference budgets remains challenging. In this work we propose a method to pre-train a smaller general-purpose language representation model called DistilBERT which can then be fine-tuned with good performances on a wide range of tasks like its larger counterparts. While most prior work investigated the use of distillation for building task-specific models we leverage knowledge distillation during the pre-training phase and show that it is possible to reduce the size of a BERT model by 4037; while retaining 9737; of its language understanding capabilities and being 6037; faster. To leverage the inductive biases learned by larger models during pre-training we introduce a triple loss combining language modeling distillation and cosine-distance losses. Our smaller faster and lighter model is cheaper to pre-train and we demonstrate its capabilities for on-device computations in a proof-of-concept experiment and a comparative on-device study.
