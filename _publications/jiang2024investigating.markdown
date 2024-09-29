---
layout: publication
title: Investigating Data Contamination For Pre45;training Language Models
authors: Jiang Minhao, Liu Ken Ziyu, Zhong Ming, Schaeffer Rylan, Ouyang Siru, Han Jiawei, Koyejo Sanmi
conference: "Arxiv"
year: 2024
bibkey: jiang2024investigating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.06059"}
tags: ['GPT', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Training Techniques']
---
Language models pre45;trained on web45;scale corpora demonstrate impressive capabilities on diverse downstream tasks. However there is increasing concern whether such capabilities might arise from evaluation datasets being included in the pre45;training corpus 45;45; a phenomenon known as textit123;data contamination125; 45;45; in a manner that artificially increases performance. There has been little understanding of how this potential contamination might influence LMs performance on downstream tasks. In this paper we explore the impact of data contamination at the pre45;training stage by pre45;training a series of GPT45;2 models textit123;from scratch125;. We highlight the effect of both text contamination (textit123;i.e.125; input text of the evaluation samples) and ground45;truth contamination (textit123;i.e.125; the prompts asked on the input and the desired outputs) from evaluation data. We also investigate the effects of repeating contamination for various downstream tasks. Additionally we examine the prevailing n45;gram45;based definitions of contamination within current LLM reports pinpointing their limitations and inadequacy. Our findings offer new insights into data contaminations effects on language model capabilities and underscore the need for independent comprehensive contamination assessments in LLM studies.
