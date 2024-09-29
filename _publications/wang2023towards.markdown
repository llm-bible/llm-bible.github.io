---
layout: publication
title: Towards Improving Document Understanding An Exploration On Text45;grounding Via Mllms
authors: Wang Yonghui, Zhou Wengang, Feng Hao, Zhou Keyi, Li Houqiang
conference: "Arxiv"
year: 2023
bibkey: wang2023towards
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.13194"}
tags: ['Fine Tuning', 'GPT', 'Model Architecture', 'Multimodal Models', 'Prompting']
---
In the field of document understanding significant advances have been made in the fine45;tuning of Multimodal Large Language Models (MLLMs) with instruction45;following data. Nevertheless the potential of text45;grounding capability within text45;rich scenarios remains underexplored. In this paper we present a text45;grounding document understanding model termed TGDoc which addresses this deficiency by enhancing MLLMs with the ability to discern the spatial positioning of text within images. Empirical evidence suggests that text45;grounding improves the models interpretation of textual content thereby elevating its proficiency in comprehending text45;rich images. Specifically we compile a dataset containing 99K PowerPoint presentations sourced from the internet. We formulate instruction tuning tasks including text detection recognition and spotting to facilitate the cohesive alignment between the visual encoder and large language model. Moreover we curate a collection of text45;rich images and prompt the text45;only GPT45;4 to generate 12K high45;quality conversations featuring textual locations within text45;rich scenarios. By integrating text location data into the instructions TGDoc is adept at discerning text locations during the visual question process. Extensive experiments demonstrate that our method achieves state45;of45;the45;art performance across multiple text45;rich benchmarks validating the effectiveness of our method.
