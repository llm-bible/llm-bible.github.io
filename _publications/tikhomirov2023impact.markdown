---
layout: publication
title: Impact Of Tokenization On Llama Russian Adaptation
authors: Tikhomirov Mikhail, Chernyshev Daniil
conference: "Arxiv"
year: 2023
bibkey: tikhomirov2023impact
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.02598"}
tags: ['Fine Tuning', 'Tokenization', 'Training Techniques']
---
Latest instruction45;tuned large language models (LLM) show great results on various tasks however they often face performance degradation for non45;English input. There is evidence that the reason lies in inefficient tokenization caused by low language representation in pre45;training data which hinders the comprehension of non45;English instructions limiting the potential of target language instruction45;tuning. In this work we investigate the possibility of addressing the issue with vocabulary substitution in the context of LLaMa Russian language adaptation. We explore three variants of vocabulary adaptation and test their performance on Saiga instruction45;tuning and fine45;tuning on Russian Super Glue benchmark. The results of automatic evaluation show that vocabulary substitution not only improves the models quality in Russian but also accelerates fine45;tuning (3537;) and inference (up to 6037;) while reducing memory consumption. Additional human evaluation of the instruction45;tuned models demonstrates that models with Russian45;adapted vocabulary generate answers with higher user preference than the original Saiga45;LLaMa model.
