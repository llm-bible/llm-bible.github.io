---
layout: publication
title: "Investigating Data Contamination For Pre-training Language Models"
authors: Jiang Minhao, Liu Ken Ziyu, Zhong Ming, Schaeffer Rylan, Ouyang Siru, Han Jiawei, Koyejo Sanmi
conference: "Arxiv"
year: 2024
bibkey: jiang2024investigating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.06059"}
tags: ['GPT', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Training Techniques']
---
Language models pre-trained on web-scale corpora demonstrate impressive capabilities on diverse downstream tasks. However there is increasing concern whether such capabilities might arise from evaluation datasets being included in the pre-training corpus -- a phenomenon known as (textit)data contamination -- in a manner that artificially increases performance. There has been little understanding of how this potential contamination might influence LMs performance on downstream tasks. In this paper we explore the impact of data contamination at the pre-training stage by pre-training a series of GPT-2 models (textit)from scratch. We highlight the effect of both text contamination ((textit)i.e. input text of the evaluation samples) and ground-truth contamination ((textit)i.e. the prompts asked on the input and the desired outputs) from evaluation data. We also investigate the effects of repeating contamination for various downstream tasks. Additionally we examine the prevailing n-gram-based definitions of contamination within current LLM reports pinpointing their limitations and inadequacy. Our findings offer new insights into data contaminations effects on language model capabilities and underscore the need for independent comprehensive contamination assessments in LLM studies.
