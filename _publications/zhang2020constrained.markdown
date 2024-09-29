---
layout: publication
title: POINTER Constrained Progressive Text Generation Via Insertion45;based Generative Pre45;training
authors: Zhang Yizhe, Wang Guoyin, Li Chunyuan, Gan Zhe, Brockett Chris, Dolan Bill
conference: "Arxiv"
year: 2020
bibkey: zhang2020constrained
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2005.00558"}
  - {name: "Code", url: "https://github.com/dreasysnail/POINTER)"}
tags: ['Applications', 'BERT', 'GPT', 'Has Code', 'Language Modeling', 'Model Architecture', 'Pretraining Methods', 'Training Techniques', 'Transformer']
---
Large45;scale pre45;trained language models such as BERT and GPT45;2 have achieved excellent performance in language representation learning and free45;form text generation. However these models cannot be directly employed to generate text under specified lexical constraints. To address this challenge we present POINTER (PrOgressive INsertion45;based TransformER) a simple yet novel insertion45;based approach for hard45;constrained text generation. The proposed method operates by progressively inserting new tokens between existing tokens in a parallel manner. This procedure is recursively applied until a sequence is completed. The resulting coarse45;to45;fine hierarchy makes the generation process intuitive and interpretable. We pre45;train our model with the proposed progressive insertion45;based objective on a 12GB Wikipedia dataset and fine45;tune it on downstream hard45;constrained generation tasks. Non45;autoregressive decoding yields an empirically logarithmic time complexity during inference time. Experimental results on both News and Yelp datasets demonstrate that POINTER achieves state45;of45;the45;art performance on constrained text generation. We released the pre45;trained models and the source code to facilitate future research (https://github.com/dreasysnail/POINTER).
