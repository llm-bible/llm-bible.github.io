---
layout: publication
title: "Faithlm: Towards Faithful Explanations For Large Language Models"
authors: Chuang Yu-neng, Wang Guanchu, Chang Chia-yuan, Tang Ruixiang, Zhong Shaochen, Yang Fan, Du Mengnan, Cai Xuanting, Hu Xia
conference: "Arxiv"
year: 2024
bibkey: chuang2024towards
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.04678"}
tags: ['Efficiency And Optimization', 'Interpretability And Explainability', 'RAG']
---
Large Language Models (LLMs) have become proficient in addressing complex tasks by leveraging their extensive internal knowledge and reasoning capabilities. However the black-box nature of these models complicates the task of explaining their decision-making processes. While recent advancements demonstrate the potential of leveraging LLMs to self-explain their predictions through natural language (NL) explanations their explanations may not accurately reflect the LLMs decision-making process due to a lack of fidelity optimization on the derived explanations. Measuring the fidelity of NL explanations is a challenging issue as it is difficult to manipulate the input context to mask the semantics of these explanations. To this end we introduce FaithLM to explain the decision of LLMs with NL explanations. Specifically FaithLM designs a method for evaluating the fidelity of NL explanations by incorporating the contrary explanations to the query process. Moreover FaithLM conducts an iterative process to improve the fidelity of derived explanations. Experiment results on three datasets from multiple domains demonstrate that FaithLM can significantly improve the fidelity of derived explanations which also provides a better alignment with the ground-truth explanations.
