---
layout: publication
title: Turning English45;centric Llms Into Polyglots How Much Multilinguality Is Needed
authors: Kew Tannon, Schottmann Florian, Sennrich Rico
conference: "Arxiv"
year: 2023
bibkey: kew2023turning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.12683"}
  - {name: "Code", url: "https://github.com/ZurichNLP/multilingual&#45;instruction&#45;tuning"}
tags: ['Applications', 'Has Code', 'Pretraining Methods', 'Training Techniques']
---
The vast majority of todays large language models are English45;centric having been pretrained predominantly on English text. Yet in order to meet user expectations models need to be able to respond appropriately in multiple languages once deployed in downstream applications. Given limited exposure to other languages during pretraining cross45;lingual transfer is important for achieving decent performance in non45;English settings. In this work we investigate just how much multilinguality is required during finetuning to elicit strong cross45;lingual generalisation across a range of tasks and target languages. We find that compared to English45;only finetuning multilingual instruction tuning with as few as three languages significantly improves a models cross45;lingual transfer abilities on generative tasks that assume input/output language agreement while being of less importance for highly structured tasks. Our code and data is available at https://github.com/ZurichNLP/multilingual&#45;instruction&#45;tuning.
