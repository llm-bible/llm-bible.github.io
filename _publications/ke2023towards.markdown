---
layout: publication
title: Critiquellm Towards An Informative Critique Generation Model For Evaluation Of Large Language Model Generation
authors: Ke Pei, Wen Bosi, Feng Zhuoer, Liu Xiao, Lei Xuanyu, Cheng Jiale, Wang Shengyuan, Zeng Aohan, Dong Yuxiao, Wang Hongning, Tang Jie, Huang Minlie
conference: "Arxiv"
year: 2023
bibkey: ke2023towards
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.18702"}
tags: ['Applications', 'GPT', 'Model Architecture', 'Prompting']
---
Since the natural language processing (NLP) community started to make large language models (LLMs) act as a critic to evaluate the quality of generated texts most of the existing works train a critique generation model on the evaluation data labeled by GPT45;4s direct prompting. We observe that these models lack the ability to generate informative critiques in both pointwise grading and pairwise comparison especially without references. As a result their generated critiques cannot provide fine45;grained distinguishability on generated texts causing unsatisfactory evaluation performance. In this paper we propose a simple yet effective method called Eval45;Instruct which can first acquire pointwise grading critiques with pseudo references and then revise these critiques via multi45;path prompting to obtain informative evaluation data in different tasks and settings including pointwise grading and pairwise comparison with / without references. After fine45;tuning on these data the resulting model CritiqueLLM is empirically shown to outperform ChatGPT and all the open45;source baselines and even achieve comparable evaluation performance to GPT45;4 in system45;level correlations of pointwise grading. We also demonstrate that our generated critiques can act as scalable feedback to further improve the generation quality of strong LLMs like ChatGPT.
