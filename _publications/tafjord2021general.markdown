---
layout: publication
title: General45;purpose Question45;answering With Macaw
authors: Tafjord Oyvind, Clark Peter
conference: "Arxiv"
year: 2021
bibkey: tafjord2021general
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2109.02593"}
  - {name: "Code", url: "https://github.com/allenai/macaw"}
tags: ['GPT', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'Training Techniques']
---
Despite the successes of pretrained language models there are still few high45;quality general45;purpose QA systems that are freely available. In response we present Macaw a versatile generative question45;answering (QA) system that we are making available to the community. Macaw is built on UnifiedQA itself built on T5 and exhibits strong performance zero45;shot on a wide variety of topics including outperforming GPT45;3 by over 1037; (absolute) on Challenge300 a suite of 300 challenge questions despite being an order of magnitude smaller (11 billion vs. 175 billion parameters). In addition Macaw allows different permutations (angles) of its inputs and outputs to be used for example Macaw can take a question and produce an answer; or take an answer and produce a question; or take an answer and question and produce multiple45;choice options. We describe the system and illustrate a variety of question types where it produces surprisingly good answers well outside the training setup. We also identify question classes where it still appears to struggle offering insights into the limitations of pretrained language models. Macaw is freely available and we hope that it proves useful to the community. Macaw is available at https://github.com/allenai/macaw
