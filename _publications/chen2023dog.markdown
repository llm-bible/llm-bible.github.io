---
layout: publication
title: Dog45;instruct Towards Premium Instruction45;tuning Data Via Text45;grounded Instruction Wrapping
authors: Chen Yongrui, Jiang Haiyun, Huang Xinting, Shi Shuming, Qi Guilin
conference: "Arxiv"
year: 2023
bibkey: chen2023dog
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.05447"}
  - {name: "Code", url: "https://github.com/Bahuia/Dog&#45;Instruct"}
tags: ['Has Code', 'Pretraining Methods', 'Training Techniques']
---
The improvement of LLMs instruction45;following capabilities relies heavily on the availability of high45;quality instruction45;response pairs. Unfortunately the current methods used to collect the pairs suffer from either unaffordable labor costs or severe hallucinations in the self45;generation of LLM. To tackle these challenges this paper proposes a scalable solution. It involves training LLMs to generate instruction45;response pairs based on human45;written documents rather than relying solely on self45;generation without context. Our proposed method not only exploits the advantages of human45;written documents in reducing hallucinations but also utilizes an LLM to wrap the expression of documents which enables us to bridge the gap between various document styles and the standard AI response. Experiments demonstrate that our method outperforms existing typical methods on multiple benchmarks. In particular compared to the best45;performing baseline the LLM trained using our generated dataset exhibits a 1037; relative improvement in performance on AlpacaEval despite utilizing only 1/5 of its training data. Furthermore a comprehensive manual evaluation validates the quality of the data we generated. Our trained wrapper is publicly available at https://github.com/Bahuia/Dog&#45;Instruct.
