---
layout: publication
title: GPT Self45;supervision For A Better Data Annotator
authors: Pei Xiaohuan, Li Yanxi, Xu Chang
conference: "Arxiv"
year: 2023
bibkey: pei2023gpt
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2306.04349"}
tags: ['GPT', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'RAG', 'Reinforcement Learning', 'Transformer']
---
The task of annotating data into concise summaries poses a significant challenge across various domains frequently requiring the allocation of significant time and specialized knowledge by human experts. Despite existing efforts to use large language models for annotation tasks significant problems such as limited applicability to unlabeled data the absence of self45;supervised methods and the lack of focus on complex structured data still persist. In this work we propose a GPT self45;supervision annotation method which embodies a generating45;recovering paradigm that leverages the one45;shot learning capabilities of the Generative Pretrained Transformer (GPT). The proposed approach comprises a one45;shot tuning phase followed by a generation phase. In the one45;shot tuning phase we sample a data from the support set as part of the prompt for GPT to generate a textual summary which is then used to recover the original data. The alignment score between the recovered and original data serves as a self45;supervision navigator to refine the process. In the generation stage the optimally selected one45;shot sample serves as a template in the prompt and is applied to generating summaries from challenging datasets. The annotation performance is evaluated by tuning several human feedback reward networks and by calculating alignment scores between original and recovered data at both sentence and structure levels. Our self45;supervised annotation method consistently achieves competitive scores convincingly demonstrating its robust strength in various data45;to45;summary annotation tasks.
