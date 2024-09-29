---
layout: publication
title: Enhancing CLIP With GPT45;4 Harnessing Visual Descriptions As Prompts
authors: Maniparambil Mayug, Vorster Chris, Molloy Derek, Murphy Noel, Mcguinness Kevin, O'connor Noel E.
conference: "Arxiv"
year: 2023
bibkey: maniparambil2023enhancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2307.11661"}
  - {name: "Code", url: "https://github.com/mayug/VDT&#45;Adapter"}
tags: ['GPT', 'Has Code', 'Model Architecture', 'Prompting', 'RAG', 'Tools']
---
Contrastive pretrained large Vision45;Language Models (VLMs) like CLIP have revolutionized visual representation learning by providing good performance on downstream datasets. VLMs are 045;shot adapted to a downstream dataset by designing prompts that are relevant to the dataset. Such prompt engineering makes use of domain expertise and a validation dataset. Meanwhile recent developments in generative pretrained models like GPT45;4 mean they can be used as advanced internet search tools. They can also be manipulated to provide visual information in any structure. In this work we show that GPT45;4 can be used to generate text that is visually descriptive and how this can be used to adapt CLIP to downstream tasks. We show considerable improvements in 045;shot transfer accuracy on specialized fine45;grained datasets like EuroSAT (~737;) DTD (~737;) SUN397 (~4.637;) and CUB (~3.337;) when compared to CLIPs default prompt. We also design a simple few45;shot adapter that learns to choose the best possible sentences to construct generalizable classifiers that outperform the recently proposed CoCoOP by ~237; on average and by over 437; on 4 specialized fine45;grained datasets. The code prompts and auxiliary text dataset is available at https://github.com/mayug/VDT&#45;Adapter.
