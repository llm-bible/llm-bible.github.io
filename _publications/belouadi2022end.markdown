---
layout: publication
title: Bygpt5 End45;to45;end Style45;conditioned Poetry Generation With Token45;free Language Models
authors: Belouadi Jonas, Eger Steffen
conference: "Arxiv"
year: 2022
bibkey: belouadi2022end
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2212.10474"}
tags: ['Efficiency And Optimization', 'GPT', 'Model Architecture', 'Tokenization', 'Training Techniques']
---
State45;of45;the45;art poetry generation systems are often complex. They either consist of task45;specific model pipelines incorporate prior knowledge in the form of manually created constraints or both. In contrast end45;to45;end models would not suffer from the overhead of having to model prior knowledge and could learn the nuances of poetry from data alone reducing the degree of human supervision required. In this work we investigate end45;to45;end poetry generation conditioned on styles such as rhyme meter and alliteration. We identify and address lack of training data and mismatching tokenization algorithms as possible limitations of past attempts. In particular we successfully pre45;train ByGPT5 a new token45;free decoder45;only language model and fine45;tune it on a large custom corpus of English and German quatrains annotated with our styles. We show that ByGPT5 outperforms other models such as mT5 ByT5 GPT45;2 and ChatGPT while also being more parameter efficient and performing favorably compared to humans. In addition we analyze its runtime performance and demonstrate that it is not prone to memorization. We make our code models and datasets publicly available.
