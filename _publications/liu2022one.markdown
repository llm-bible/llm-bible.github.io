---
layout: publication
title: Deplot One45;shot Visual Language Reasoning By Plot45;to45;table Translation
authors: Liu Fangyu, Eisenschlos Julian Martin, Piccinno Francesco, Krichene Syrine, Pang Chenxi, Lee Kenton, Joshi Mandar, Chen Wenhu, Collier Nigel, Altun Yasemin
conference: "Arxiv"
year: 2022
bibkey: liu2022one
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2212.10505"}
tags: ['Ethics And Bias', 'Prompting', 'Reinforcement Learning', 'Training Techniques']
---
Visual language such as charts and plots is ubiquitous in the human world. Comprehending plots and charts requires strong reasoning skills. Prior state45;of45;the45;art (SOTA) models require at least tens of thousands of training examples and their reasoning capabilities are still much limited especially on complex human45;written queries. This paper presents the first one45;shot solution to visual language reasoning. We decompose the challenge of visual language reasoning into two steps (1) plot45;to45;text translation and (2) reasoning over the translated text. The key in this method is a modality conversion module named as DePlot which translates the image of a plot or chart to a linearized table. The output of DePlot can then be directly used to prompt a pretrained large language model (LLM) exploiting the few45;shot reasoning capabilities of LLMs. To obtain DePlot we standardize the plot45;to45;table task by establishing unified task formats and metrics and train DePlot end45;to45;end on this task. DePlot can then be used off45;the45;shelf together with LLMs in a plug45;and45;play fashion. Compared with a SOTA model finetuned on more than 28k data points DePlot+LLM with just one45;shot prompting achieves a 24.037; improvement over finetuned SOTA on human45;written queries from the task of chart QA.
