---
layout: publication
title: An Emulator For Fine45;tuning Large Language Models Using Small Language Models
authors: Mitchell Eric, Rafailov Rafael, Sharma Archit, Finn Chelsea, Manning Christopher D.
conference: "Arxiv"
year: 2023
bibkey: mitchell2023emulator
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.12962"}
tags: ['Pretraining Methods', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
Widely used language models (LMs) are typically built by scaling up a two45;stage training pipeline a pre45;training stage that uses a very large diverse dataset of text and a fine45;tuning (sometimes alignment) stage that uses targeted examples or other specifications of desired behaviors. While it has been hypothesized that knowledge and skills come from pre45;training and fine45;tuning mostly filters this knowledge and skillset this intuition has not been extensively tested. To aid in doing so we introduce a novel technique for decoupling the knowledge and skills gained in these two stages enabling a direct answer to the question What would happen if we combined the knowledge learned by a large model during pre45;training with the knowledge learned by a small model during fine45;tuning (or vice versa) Using an RL45;based framework derived from recent developments in learning from human preferences we introduce emulated fine45;tuning (EFT) a principled and practical method for sampling from a distribution that approximates (or emulates) the result of pre45;training and fine45;tuning at different scales. Our experiments with EFT show that scaling up fine45;tuning tends to improve helpfulness while scaling up pre45;training tends to improve factuality. Beyond decoupling scale we show that EFT enables test45;time adjustment of competing behavioral traits like helpfulness and harmlessness without additional training. Finally a special case of emulated fine45;tuning which we call LM up45;scaling avoids resource45;intensive fine45;tuning of large pre45;trained models by ensembling them with small fine45;tuned models essentially emulating the result of fine45;tuning the large pre45;trained model. Up45;scaling consistently improves helpfulness and factuality of instruction45;following models in the Llama Llama45;2 and Falcon families without additional hyperparameters or training.
