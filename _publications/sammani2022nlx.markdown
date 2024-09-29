---
layout: publication
title: NLX45;GPT A Model For Natural Language Explanations In Vision And Vision45;language Tasks
authors: Sammani Fawaz, Mukherjee Tanmoy, Deligiannis Nikos
conference: "Arxiv"
year: 2022
bibkey: sammani2022nlx
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2203.05081"}
  - {name: "Code", url: "https://github.com/fawazsammani/nlxgpt"}
tags: ['Ethics And Bias', 'GPT', 'Has Code', 'Interpretability And Explainability', 'Model Architecture', 'Security', 'Tools', 'Training Techniques']
---
Natural language explanation (NLE) models aim at explaining the decision45;making process of a black box system via generating natural language sentences which are human45;friendly high45;level and fine45;grained. Current NLE models explain the decision45;making process of a vision or vision45;language model (a.k.a. task model) e.g. a VQA model via a language model (a.k.a. explanation model) e.g. GPT. Other than the additional memory resources and inference time required by the task model the task and explanation models are completely independent which disassociates the explanation from the reasoning process made to predict the answer. We introduce NLX45;GPT a general compact and faithful language model that can simultaneously predict an answer and explain it. We first conduct pre45;training on large scale data of image45;caption pairs for general understanding of images and then formulate the answer as a text prediction task along with the explanation. Without region proposals nor a task model our resulting overall framework attains better evaluation scores contains much less parameters and is 15× faster than the current SoA model. We then address the problem of evaluating the explanations which can be in many times generic data45;biased and can come in several forms. We therefore design 2 new evaluation measures (1) explain45;predict and (2) retrieval45;based attack a self45;evaluation framework that requires no labels. Code is at https://github.com/fawazsammani/nlxgpt.
