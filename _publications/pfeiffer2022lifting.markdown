---
layout: publication
title: Lifting The Curse Of Multilinguality By Pre45;training Modular Transformers
authors: Pfeiffer Jonas, Goyal Naman, Lin Xi Victoria, Li Xian, Cross James, Riedel Sebastian, Artetxe Mikel
conference: "Arxiv"
year: 2022
bibkey: pfeiffer2022lifting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2205.06266"}
tags: ['Applications', 'Model Architecture', 'Pretraining Methods', 'Training Techniques', 'Transformer']
---
Multilingual pre45;trained models are known to suffer from the curse of multilinguality which causes per45;language performance to drop as they cover more languages. We address this issue by introducing language45;specific modules which allows us to grow the total capacity of the model while keeping the total number of trainable parameters per language constant. In contrast with prior work that learns language45;specific components post45;hoc we pre45;train the modules of our Cross45;lingual Modular (X45;Mod) models from the start. Our experiments on natural language inference named entity recognition and question answering show that our approach not only mitigates the negative interference between languages but also enables positive transfer resulting in improved monolingual and cross45;lingual performance. Furthermore our approach enables adding languages post45;hoc with no measurable drop in performance no longer limiting the model usage to the set of pre45;trained languages.
