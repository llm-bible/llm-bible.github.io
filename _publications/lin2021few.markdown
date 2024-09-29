---
layout: publication
title: Few45;shot Learning With Multilingual Language Models
authors: Lin Xi Victoria, Mihaylov Todor, Artetxe Mikel, Wang Tianlu, Chen Shuohui, Simig Daniel, Ott Myle, Goyal Naman, Bhosale Shruti, Du Jingfei, Pasunuru Ramakanth, Shleifer Sam, Koura Punit Singh, Chaudhary Vishrav, O'horo Brian, Wang Jeff, Zettlemoyer Luke, Kozareva Zornitsa, Diab Mona, Stoyanov Veselin, Li Xian
conference: "Arxiv"
year: 2021
bibkey: lin2021few
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2112.10668"}
tags: ['Applications', 'GPT', 'Model Architecture', 'Prompting', 'Training Techniques']
---
Large45;scale generative language models such as GPT45;3 are competitive few45;shot learners. While these models are known to be able to jointly represent many different languages their training data is dominated by English potentially limiting their cross45;lingual generalization. In this work we train multilingual generative language models on a corpus covering a diverse set of languages and study their few45; and zero45;shot learning capabilities in a wide range of tasks. Our largest model with 7.5 billion parameters sets new state of the art in few45;shot learning in more than 20 representative languages outperforming GPT45;3 of comparable size in multilingual commonsense reasoning (with +7.437; absolute accuracy improvement in 045;shot settings and +9.437; in 445;shot settings) and natural language inference (+5.437; in each of 045;shot and 445;shot settings). On the FLORES45;101 machine translation benchmark our model outperforms GPT45;3 on 171 out of 182 directions with 32 training examples while surpassing the official supervised baseline in 45 directions. We conduct an in45;depth analysis of different multilingual prompting approaches showing in particular that strong few45;shot learning performance across languages can be achieved via cross45;lingual transfer through both templates and demonstration examples. Finally we evaluate our models in social value tasks such as hate speech detection in five languages and find it has limitations similar to comparable sized GPT45;3 models.
