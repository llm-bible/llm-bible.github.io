---
layout: publication
title: ArthModel Enhance Arithmetic Skills to Large Language Model
authors: Guo Yingdi
conference: "Arxiv"
year: 2023
bibkey: guo2023arthmodel
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.18609"}
  - {name: "Code", url: "https://github.com/eteced/arithmetic_finetuning_v1"}
tags: ['GPT', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
With the great success of ChatGPT the research of large language models has become increasingly popular. However the models have several limitations such as toxicity and pool performance of arithmetic solving. Meanwhile LLM may have some potential abilities that have yet to be exploited. In this paper we choose a different way to enhance the arithmetic ability of LLM. We propose to train LLM to generate a postfix expression related to the arithmetic problem and incorporate it with small pretrained models. Moreover this small model transfers the token embeddings into real dense numbers and invokes native functions of a deep learning platform to get the correct answer. To generate the final result we propose prompt injection for adding the result outputs by the small model to LLM. This work provides different ways of thinking training and using a language model. The codes and models will be released at url https://github.com/eteced/arithmetic_finetuning_v1.
