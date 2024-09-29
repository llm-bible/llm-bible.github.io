---
layout: publication
title: Reasoning In Large Language Models Through Symbolic Math Word Problems
authors: Gaur Vedant, Saunshi Nikunj
conference: "Arxiv"
year: 2023
bibkey: gaur2023reasoning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2308.01906"}
tags: ['GPT', 'Interpretability And Explainability', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'RAG']
---
Large language models (LLMs) have revolutionized NLP by solving downstream tasks with little to no labeled data. Despite their versatile abilities the larger question of their ability to reason remains ill45;understood. This paper addresses reasoning in math word problems (MWPs) by studying symbolic versions of the numeric problems since a symbolic expression is a concise explanation of the numeric answer. We create and use a symbolic version of the SVAMP dataset and find that GPT45;3s davinci45;002 model also has good zero45;shot accuracy on symbolic MWPs. To evaluate the faithfulness of the models reasoning we go beyond accuracy and additionally evaluate the alignment between the final answer and the outputted reasoning which correspond to numeric and symbolic answers respectively for MWPs. We explore a self45;prompting approach to encourage the symbolic reasoning to align with the numeric answer thus equipping the LLM with the ability to provide a concise and verifiable reasoning and making it more interpretable. Surprisingly self45;prompting also improves the symbolic accuracy to be higher than both the numeric and symbolic accuracies thus providing an ensembling effect. The SVAMP95;Sym dataset will be released for future research on symbolic math problems.
