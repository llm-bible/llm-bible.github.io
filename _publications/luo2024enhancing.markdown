---
layout: publication
title: Knowla\: Enhancing Parameter-efficient Finetuning With Knowledgeable Adaptation
authors: Luo Xindi, Sun Zequn, Zhao Jing, Zhao Zhe, Hu Wei
conference: "Arxiv"
year: 2024
bibkey: luo2024enhancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.14950"}
tags: ['Applications', 'Fine Tuning', 'Prompting', 'RAG', 'Security']
---
Parameter-efficient finetuning (PEFT) is a key technique for adapting large language models (LLMs) to downstream tasks. In this paper we study leveraging knowledge graph embeddings to improve the effectiveness of PEFT. We propose a knowledgeable adaptation method called KnowLA. It inserts an adaptation layer into an LLM to integrate the embeddings of entities appearing in the input text. The adaptation layer is trained in combination with LoRA on instruction data. Experiments on six benchmarks with two popular LLMs and three knowledge graphs demonstrate the effectiveness and robustness of KnowLA. We show that (modelname) can help activate the relevant parameterized knowledge in an LLM to answer a question without changing its parameters or input prompts.
