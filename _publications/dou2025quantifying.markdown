---
layout: publication
title: 'Evalearn: Quantifying The Learning Capability And Efficiency Of Llms Via Sequential Problem Solving'
authors: Shihan Dou, Ming Zhang, Chenhao Huang, Jiayi Chen, Feng Chen, Shichun Liu, Yan Liu, Chenxiao Liu, Cheng Zhong, Zongzhang Zhang, Tao Gui, Chao Xin, Wei Chengzhi, Lin Yan, Qi Zhang, Yonghui Wu, Xuanjing Huang
conference: "Arxiv"
year: 2025
bibkey: dou2025quantifying
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2506.02672"}
tags: ['RAG', 'Efficiency and Optimization', 'Tools']
---
We introduce EvaLearn, a pioneering benchmark designed to evaluate large language models (LLMs) on their learning capability and efficiency in challenging tasks, a critical, yet underexplored aspect of model potential. EvaLearn contains 648 challenging problems across six task types, grouped into 182 sequences, each sequence dedicated to one task type. Diverging from most existing benchmarks that evaluate models in parallel, EvaLearn requires models to solve problems sequentially, allowing them to leverage the experience gained from previous solutions. EvaLearn provides five comprehensive automated metrics to evaluate models and quantify their learning capability and efficiency. We extensively benchmark nine frontier models and observe varied performance profiles: some models, such as Claude-3.7-sonnet, start with moderate initial performance but exhibit strong learning ability, while some models struggle to benefit from experience and may even show negative transfer. Moreover, we investigate model performance under two learning settings and find that instance-level rubrics and teacher-model feedback further facilitate model learning. Importantly, we observe that current LLMs with stronger static abilities do not show a clear advantage in learning capability across all tasks, highlighting that EvaLearn evaluates a new dimension of model performance. We hope EvaLearn provides a novel evaluation perspective for assessing LLM potential and understanding the gap between models and human capabilities, promoting the development of deeper and more dynamic evaluation approaches. All datasets, the automatic evaluation framework, and the results studied in this paper are available at the GitHub repository.
