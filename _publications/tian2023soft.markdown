---
layout: publication
title: 'Soft-prompt Tuning For Large Language Models To Evaluate Bias'
authors: Tian Jacob-junqi, Emerson David, Miyandoab Sevil Zanjani, Pandya Deval, Seyyed-kalantari Laleh, Khattak Faiza Khan
conference: "Arxiv"
year: 2023
bibkey: tian2023soft
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2306.04735"}
tags: ['Applications', 'Bias Mitigation', 'Ethics And Bias', 'Fairness', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'RAG', 'Reinforcement Learning', 'Transformer']
---
Prompting large language models has gained immense popularity in recent years
due to the advantage of producing good results even without the need for
labelled data. However, this requires prompt tuning to get optimal prompts that
lead to better model performances. In this paper, we explore the use of
soft-prompt tuning on sentiment classification task to quantify the biases of
large language models (LLMs) such as Open Pre-trained Transformers (OPT) and
Galactica language model. Since these models are trained on real-world data
that could be prone to bias toward certain groups of populations, it is
important to identify these underlying issues. Using soft-prompts to evaluate
bias gives us the extra advantage of avoiding the human-bias injection that can
be caused by manually designed prompts. We check the model biases on different
sensitive attributes using the group fairness (bias) and find interesting bias
patterns. Since LLMs have been used in the industry in various applications, it
is crucial to identify the biases before deploying these models in practice. We
open-source our pipeline and encourage industry researchers to adapt our work
to their use cases.
