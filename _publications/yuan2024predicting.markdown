---
layout: publication
title: Predicting Rewards Alongside Tokens Non45;disruptive Parameter Insertion For Efficient Inference Intervention In Large Language Model
authors: Yuan Chenhan, Huang Fei, Peng Ru, Lu Keming, Yu Bowen, Zhou Chang, Zhou Jingren
conference: "Arxiv"
year: 2024
bibkey: yuan2024predicting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.10764"}
  - {name: "Code", url: "https://github.com/chenhan97/Otter&#125;"}
tags: ['Has Code', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Transformer']
---
Transformer45;based large language models (LLMs) exhibit limitations such as generating unsafe responses unreliable reasoning etc. Existing inference intervention approaches attempt to mitigate these issues by finetuning additional models to produce calibration signals (such as rewards) that guide the LLMs decoding process. However this solution introduces substantial time and space overhead due to the separate models required. This work proposes Non45;disruptive parameters insertion (Otter) inserting extra parameters into the transformer architecture to predict calibration signals along with the original LLM output. Otter offers state45;of45;the45;art performance on multiple demanding tasks while saving up to 86.537; extra space and 98.537; extra time. Furthermore Otter seamlessly integrates with existing inference engines requiring only a one45;line code change and the original model response remains accessible after the parameter insertion. Our code is publicly available at url123;https://github.com/chenhan97/Otter&#125;
