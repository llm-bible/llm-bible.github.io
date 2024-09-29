---
layout: publication
title: Jetmoe Reaching Llama2 Performance With 0.1M Dollars
authors: Shen Yikang, Guo Zhen, Cai Tianle, Qin Zengyi
conference: "Arxiv"
year: 2024
bibkey: shen2024reaching
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.07413"}
  - {name: "Code", url: "https://github.com/myshell&#45;ai/JetMoE"}
tags: ['Attention Mechanism', 'Ethics And Bias', 'Has Code', 'Model Architecture', 'RAG', 'TACL', 'Training Techniques']
---
Large Language Models (LLMs) have achieved remarkable results but their increasing resource demand has become a major obstacle to the development of powerful and accessible super45;human intelligence. This report introduces JetMoE45;8B a new LLM trained with less than 0.1 million using 1.25T tokens from carefully mixed open45;source corpora and 30000 H100 GPU hours. Despite its low cost the JetMoE45;8B demonstrates impressive performance with JetMoE45;8B outperforming the Llama245;7B model and JetMoE45;8B45;Chat surpassing the Llama245;13B45;Chat model. These results suggest that LLM training can be much more cost45;effective than generally thought. JetMoE45;8B is based on an efficient Sparsely45;gated Mixture45;of45;Experts (SMoE) architecture composed of attention and feedforward experts. Both layers are sparsely activated allowing JetMoE45;8B to have 8B parameters while only activating 2B for each input token reducing inference computation by about 7037; compared to Llama245;7B. Moreover JetMoE45;8B is highly open and academia45;friendly using only public datasets and training code. All training parameters and data mixtures have been detailed in this report to facilitate future efforts in the development of open foundation models. This transparency aims to encourage collaboration and further advancements in the field of accessible and efficient LLMs. The model weights are publicly available at https://github.com/myshell&#45;ai/JetMoE.
