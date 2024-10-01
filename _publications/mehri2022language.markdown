---
layout: publication
title: 'LAD: Language Models As Data For Zero-shot Dialog'
authors: Mehri Shikib, Altun Yasemin, Eskenazi Maxine
conference: "Arxiv"
year: 2022
bibkey: mehri2022language
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2207.14393"}
  - {name: "Code", url: "https://github.com/Shikib/lad"}
tags: ['GPT', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Training Techniques']
---
To facilitate zero-shot generalization in taskoriented dialog, this paper proposes Language Models as Data (LAD). LAD is a paradigm for creating diverse and accurate synthetic data which conveys the necessary structural constraints and can be used to train a downstream neural dialog model. LAD leverages GPT-3 to induce linguistic diversity. LAD achieves significant performance gains in zero-shot settings on intent prediction (+15&#37;), slot filling (+31.4 F-1) and next action prediction (+11 F1). Furthermore, an interactive human evaluation shows that training with LAD is competitive with training on human dialogs. LAD is open-sourced, with the code and data available at https://github.com/Shikib/lad.
