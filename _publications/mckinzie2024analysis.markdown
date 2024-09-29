---
layout: publication
title: MM1 Methods Analysis amp; Insights From Multimodal LLM Pre45;training
authors: Mckinzie Brandon, Gan Zhe, Fauconnier Jean-philippe, Dodge Sam, Zhang Bowen, Dufter Philipp, Shah Dhruti, Du Xianzhi, Peng Futang, Weers Floris, Belyi Anton, Zhang Haotian, Singh Karanjeet, Kang Doug, Jain Ankur, Hè Hongyu, Schwarzer Max, Gunter Tom, Kong Xiang, Zhang Aonan, Wang Jianyu, Wang Chong, Du Nan, Lei Tao, Wiseman Sam, Yin Guoli, Lee Mark, Wang Zirui, Pang Ruoming, Grasch Peter, Toshev Alexander, Yang Yinfei
conference: "Arxiv"
year: 2024
bibkey: mckinzie2024analysis
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.09611"}
tags: ['Model Architecture', 'Multimodal Models', 'Prompting', 'Reinforcement Learning', 'Training Techniques']
---
In this work we discuss building performant Multimodal Large Language Models (MLLMs). In particular we study the importance of various architecture components and data choices. Through careful and comprehensive ablations of the image encoder the vision language connector and various pre45;training data choices we identified several crucial design lessons. For example we demonstrate that for large45;scale multimodal pre45;training using a careful mix of image45;caption interleaved image45;text and text45;only data is crucial for achieving state45;of45;the45;art (SOTA) few45;shot results across multiple benchmarks compared to other published pre45;training results. Further we show that the image encoder together with image resolution and the image token count has substantial impact while the vision45;language connector design is of comparatively negligible importance. By scaling up the presented recipe we build MM1 a family of multimodal models up to 30B parameters including both dense models and mixture45;of45;experts (MoE) variants that are SOTA in pre45;training metrics and achieve competitive performance after supervised fine45;tuning on a range of established multimodal benchmarks. Thanks to large45;scale pre45;training MM1 enjoys appealing properties such as enhanced in45;context learning and multi45;image reasoning enabling few45;shot chain45;of45;thought prompting.
