---
layout: publication
title: Deltalm Encoder45;decoder Pre45;training For Language Generation And Translation By Augmenting Pretrained Multilingual Encoders
authors: Ma Shuming, Dong Li, Huang Shaohan, Zhang Dongdong, Muzio Alexandre, Singhal Saksham, Awadalla Hany Hassan, Song Xia, Wei Furu
conference: "Arxiv"
year: 2021
bibkey: ma2021encoder
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2106.13736"}
  - {name: "Code", url: "https://aka.ms/deltalm&#125;"}
tags: ['Applications', 'Has Code', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
While pretrained encoders have achieved success in various natural language understanding (NLU) tasks there is a gap between these pretrained encoders and natural language generation (NLG). NLG tasks are often based on the encoder45;decoder framework where the pretrained encoders can only benefit part of it. To reduce this gap we introduce DeltaLM a pretrained multilingual encoder45;decoder model that regards the decoder as the task layer of off45;the45;shelf pretrained encoders. Specifically we augment the pretrained multilingual encoder with a decoder and pre45;train it in a self45;supervised way. To take advantage of both the large45;scale monolingual data and bilingual data we adopt the span corruption and translation span corruption as the pre45;training tasks. Experiments show that DeltaLM outperforms various strong baselines on both natural language generation and translation tasks including machine translation abstractive text summarization data45;to45;text and question generation. The code and pretrained models are available at url123;https://aka.ms/deltalm&#125;.
