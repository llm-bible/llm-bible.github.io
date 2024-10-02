---
layout: publication
title: 'Conpet: Continual Parameter-efficient Tuning For Large Language Models'
authors: Song Chenyang, Han Xu, Zeng Zheni, Li Kuai, Chen Chen, Liu Zhiyuan, Sun Maosong, Yang Tao
conference: "Arxiv"
year: 2023
bibkey: song2023continual
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.14763"}
  - {name: "Code", url: "https://github.com/Raincleared-Song/ConPET"}
tags: ['Fine Tuning', 'Has Code', 'Merging', 'Training Techniques']
---
'Continual learning necessitates the continual adaptation of models to newly emerging tasks while minimizing the catastrophic forgetting of old ones. This is extremely challenging for large language models (LLMs) with vanilla full-parameter tuning due to high computation costs, memory consumption, and forgetting issue. Inspired by the success of parameter-efficient tuning (PET), we propose Continual Parameter-Efficient Tuning (ConPET), a generalizable paradigm for continual task adaptation of LLMs with task-number-independent training complexity. ConPET includes two versions with different application scenarios. First, Static ConPET can adapt former continual learning methods originally designed for relatively smaller models to LLMs through PET and a dynamic replay strategy, which largely reduces the tuning costs and alleviates the over-fitting and forgetting issue. Furthermore, to maintain scalability, Dynamic ConPET adopts separate PET modules for different tasks and a PET module selector for dynamic optimal selection. In our extensive experiments, the adaptation of Static ConPET helps multiple former methods reduce the scale of tunable parameters by over 3,000 times and surpass the PET-only baseline by at least 5 points on five smaller benchmarks, while Dynamic ConPET gains its advantage on the largest dataset. The codes and datasets are available at https://github.com/Raincleared-Song/ConPET.'
