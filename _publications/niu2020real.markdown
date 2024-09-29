---
layout: publication
title: Real45;time Execution Of Large45;scale Language Models On Mobile
authors: Niu Wei, Kong Zhenglun, Yuan Geng, Jiang Weiwen, Guan Jiexiong, Ding Caiwen, Zhao Pu, Liu Sijia, Ren Bin, Wang Yanzhi
conference: "Arxiv"
year: 2020
bibkey: niu2020real
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2009.06823"}
tags: ['BERT', 'Efficiency And Optimization', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Tools', 'Transformer']
---
Pre45;trained large45;scale language models have increasingly demonstrated high accuracy on many natural language processing (NLP) tasks. However the limited weight storage and computational speed on hardware platforms have impeded the popularity of pre45;trained models especially in the era of edge computing. In this paper we seek to find the best model structure of BERT for a given computation size to match specific devices. We propose the first compiler45;aware neural architecture optimization framework. Our framework can guarantee the identified model to meet both resource and real45;time specifications of mobile devices thus achieving real45;time execution of large transformer45;based models like BERT variants. We evaluate our model on several NLP tasks achieving competitive results on well45;known benchmarks with lower latency on mobile devices. Specifically our model is 5.2x faster on CPU and 4.1x faster on GPU with 0.545;237; accuracy loss compared with BERT45;base. Our overall framework achieves up to 7.8x speedup compared with TensorFlow45;Lite with only minor accuracy loss.
