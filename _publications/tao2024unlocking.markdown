---
layout: publication
title: Unlocking The Potential Of Model Merging For Low45;resource Languages
authors: Tao Mingxu, Zhang Chen, Huang Quzhe, Ma Tianyao, Huang Songfang, Zhao Dongyan, Feng Yansong
conference: "Arxiv"
year: 2024
bibkey: tao2024unlocking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.03994"}
tags: ['Efficiency And Optimization', 'Fine Tuning', 'Language Modeling', 'Merging', 'Pretraining Methods', 'Training Techniques']
---
Adapting large language models (LLMs) to new languages typically involves continual pre45;training (CT) followed by supervised fine45;tuning (SFT). However this CT45;then45;SFT approach struggles with limited data in the context of low45;resource languages failing to balance language modeling and task45;solving capabilities. We thus propose model merging as an alternative for low45;resource languages combining models with distinct capabilities into a single model without additional training. We use model merging to develop task45;solving LLMs for low45;resource languages without SFT data in the target languages. Our experiments based on Llama45;245;7B demonstrate that model merging effectively endows LLMs for low45;resource languages with task45;solving abilities outperforming CT45;then45;SFT in scenarios with extremely scarce data. Observing performance saturation in model merging with more training tokens we further analyze the merging process and introduce a slack variable to the model merging algorithm to mitigate the loss of important parameters thereby enhancing performance. We hope that model merging can benefit more human languages suffering from data scarcity with its higher data efficiency.
