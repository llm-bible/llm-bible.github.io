---
layout: publication
title: 'Exploring Parameter-efficient Fine-tuning Techniques For Code Generation With Large Language Models'
authors: Martin Weyssow, Xin Zhou, Kisub Kim, David Lo, Houari Sahraoui
conference: "Arxiv"
year: 2023
bibkey: weyssow2023exploring
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2308.10462'}
  - {name: "Code", url: 'https://github.com/martin-wey/peft-llm-code/'}
tags: ['Has Code', 'RAG', 'Efficiency and Optimization', 'Applications', 'Training Techniques', 'Quantization', 'Fine-Tuning', 'Prompting', 'Survey Paper', 'Reinforcement Learning', 'In-Context Learning', 'Pretraining Methods']
---
Large language models (LLMs) demonstrate impressive capabilities to generate
accurate code snippets given natural language intents in a zero-shot manner,
i.e., without the need for specific fine-tuning. While prior studies have
highlighted the advantages of fine-tuning LLMs, this process incurs high
computational costs, making it impractical in resource-scarce environments,
particularly for models with billions of parameters. To address these
challenges, previous research explored in-context learning (ICL) and
retrieval-augmented generation (RAG) as strategies to guide the LLM generative
process with task-specific prompt examples. However, ICL and RAG introduce
inconveniences, such as the need for designing contextually relevant prompts
and the absence of learning task-specific parameters, thereby limiting
downstream task performance. In this context, we foresee parameter-efficient
fine-tuning (PEFT) as a promising approach to efficiently specialize LLMs to
task-specific data while maintaining reasonable resource consumption. In this
paper, we deliver a comprehensive study of PEFT techniques for LLMs in the
context of automated code generation. Our comprehensive investigation of PEFT
techniques for LLMs reveals their superiority and potential over ICL and RAG
across a diverse set of LLMs and three representative Python code generation
datasets: Conala, CodeAlpacaPy, and APPS. Furthermore, our study highlights the
potential for tuning larger LLMs and significant reductions in memory usage by
combining PEFT with quantization. Therefore, this study opens opportunities for
broader applications of PEFT in software engineering scenarios. Our code is
available at https://github.com/martin-wey/peft-llm-code/.
