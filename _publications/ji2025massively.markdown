---
layout: publication
title: 'Massively Multilingual Adaptation Of Large Language Models Using Bilingual Translation Data'
authors: Shaoxiong Ji, Zihao Li, Jaakko Paavola, Indraneil Paul, Hengyu Luo, Jörg Tiedemann
conference: "Arxiv"
year: 2025
bibkey: ji2025massively
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2506.00469'}
tags: ['Reinforcement Learning', 'Pre-Training', 'Training Techniques']
---
This paper investigates a critical design decision in the practice of massively multilingual continual pre-training -- the inclusion of parallel data. Specifically, we study the impact of bilingual translation data for massively multilingual language adaptation of the Llama3 family of models to 500 languages. To this end, we construct the MaLA bilingual translation corpus, containing data from more than 2,500 language pairs. Subsequently, we develop the EMMA-500 Llama 3 suite of four massively multilingual models -- continually pre-trained from the Llama 3 family of base models extensively on diverse data mixes up to 671B tokens -- and explore the effect of continual pre-training with or without bilingual translation data. Comprehensive evaluation across 7 tasks and 12 benchmarks demonstrates that bilingual data tends to enhance language transfer and performance, particularly for low-resource languages. We open-source the MaLA corpus, EMMA-500 Llama 3 suite artefacts, code, and model generations.
