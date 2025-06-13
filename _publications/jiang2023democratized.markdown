---
layout: publication
title: 'Llm4causal: Democratized Causal Tools For Everyone Via Large Language Model'
authors: Haitao Jiang, Lin Ge, Yuhe Gao, Jianian Wang, Rui Song
conference: "Arxiv"
year: 2023
bibkey: jiang2023democratized
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.17122"}
tags: ['Training Techniques', 'Model Architecture', 'Tools', 'GPT', 'Pretraining Methods', 'Fine-Tuning', 'Prompting']
---
Large Language Models (LLMs) have shown their success in language
understanding and reasoning on general topics. However, their capability to
perform inference based on user-specified structured data and knowledge in
corpus-rare concepts, such as causal decision-making is still limited. In this
work, we explore the possibility of fine-tuning an open-sourced LLM into
LLM4Causal, which can identify the causal task, execute a corresponding
function, and interpret its numerical results based on users' queries and the
provided dataset. Meanwhile, we propose a data generation process for more
controllable GPT prompting and present two instruction-tuning datasets: (1)
Causal-Retrieval-Bench for causal problem identification and input parameter
extraction for causal function calling and (2) Causal-Interpret-Bench for
in-context causal interpretation. By conducting end-to-end evaluations and two
ablation studies, we showed that LLM4Causal can deliver end-to-end solutions
for causal problems and provide easy-to-understand answers, which significantly
outperforms the baselines.
