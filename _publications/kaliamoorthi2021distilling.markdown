---
layout: publication
title: Distilling Large Language Models Into Tiny And Effective Students Using Pqrnn
authors: Kaliamoorthi Prabhu, Siddhant Aditya, Li Edward, Johnson Melvin
conference: "Arxiv"
year: 2021
bibkey: kaliamoorthi2021distilling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2101.08890"}
tags: ['Applications', 'BERT', 'Distillation', 'Efficiency And Optimization', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Training Techniques', 'Transformer']
---
Large pre-trained multilingual models like mBERT XLM-R achieve state of the art results on language understanding tasks. However they are not well suited for latency critical applications on both servers and edge devices. Its important to reduce the memory and compute resources required by these models. To this end we propose pQRNN a projection-based embedding-free neural encoder that is tiny and effective for natural language processing tasks. Without pre-training pQRNNs significantly outperform LSTM models with pre-trained embeddings despite being 140x smaller. With the same number of parameters they outperform transformer baselines thereby showcasing their parameter efficiency. Additionally we show that pQRNNs are effective student architectures for distilling large pre-trained language models. We perform careful ablations which study the effect of pQRNN parameters data augmentation and distillation settings. On MTOP a challenging multilingual semantic parsing dataset pQRNN students achieve 95.937; of the performance of an mBERT teacher while being 350x smaller. On mATIS a popular parsing task pQRNN students on average are able to get to 97.137; of the teacher while again being 350x smaller. Our strong results suggest that our approach is great for latency-sensitive applications while being able to leverage large mBERT-like models.
