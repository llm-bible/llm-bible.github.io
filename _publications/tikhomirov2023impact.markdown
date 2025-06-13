---
layout: publication
title: 'Impact Of Tokenization On Llama Russian Adaptation'
authors: Mikhail Tikhomirov, Daniil Chernyshev
conference: "Arxiv"
year: 2023
bibkey: tikhomirov2023impact
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.02598"}
tags: ['Training Techniques', 'Tokenization', 'Pretraining Methods', 'Fine-Tuning', 'Pre-Training']
---
Latest instruction-tuned large language models (LLM) show great results on
various tasks, however, they often face performance degradation for non-English
input. There is evidence that the reason lies in inefficient tokenization
caused by low language representation in pre-training data which hinders the
comprehension of non-English instructions, limiting the potential of target
language instruction-tuning. In this work we investigate the possibility of
addressing the issue with vocabulary substitution in the context of LLaMa
Russian language adaptation. We explore three variants of vocabulary adaptation
and test their performance on Saiga instruction-tuning and fine-tuning on
Russian Super Glue benchmark. The results of automatic evaluation show that
vocabulary substitution not only improves the model's quality in Russian but
also accelerates fine-tuning (35%) and inference (up to 60%) while reducing
memory consumption. Additional human evaluation of the instruction-tuned models
demonstrates that models with Russian-adapted vocabulary generate answers with
higher user preference than the original Saiga-LLaMa model.
