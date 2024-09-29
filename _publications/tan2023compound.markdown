---
layout: publication
title: Compound Text45;guided Prompt Tuning Via Image45;adaptive Cues
authors: Tan Hao, Li Jun, Zhou Yizhuang, Wan Jun, Lei Zhen, Zhang Xiangyu
conference: "Arxiv"
year: 2023
bibkey: tan2023compound
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.06401"}
  - {name: "Code", url: "https://github.com/EricTan7/TGP&#45;T"}
tags: ['Efficiency And Optimization', 'Has Code', 'Prompting', 'Tools', 'Training Techniques']
---
Vision45;Language Models (VLMs) such as CLIP have demonstrated remarkable generalization capabilities to downstream tasks. However existing prompt tuning based frameworks need to parallelize learnable textual inputs for all categories suffering from massive GPU memory consumption when there is a large number of categories in the target dataset. Moreover previous works require to include category names within prompts exhibiting subpar performance when dealing with ambiguous category names. To address these shortcomings we propose Compound Text45;Guided Prompt Tuning (TGP45;T) that significantly reduces resource demand while achieving superior performance. We introduce text supervision to the optimization of prompts which enables two benefits 1) releasing the model reliance on the pre45;defined category names during inference thereby enabling more flexible prompt generation; 2) reducing the number of inputs to the text encoder which decreases GPU memory consumption significantly. Specifically we found that compound text supervisions i.e. category45;wise and content45;wise is highly effective since they provide inter45;class separability and capture intra45;class variations respectively. Moreover we condition the prompt generation on visual features through a module called Bonder which facilitates the alignment between prompts and visual features. Extensive experiments on few45;shot recognition and domain generalization demonstrate that TGP45;T achieves superior performance with consistently lower training costs. It reduces GPU memory usage by 9337; and attains a 2.537; performance gain on 1645;shot ImageNet. The code is available at https://github.com/EricTan7/TGP&#45;T.
