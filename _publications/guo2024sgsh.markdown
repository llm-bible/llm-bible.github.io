---
layout: publication
title: SGSH Stimulate Large Language Models with Skeleton Heuristics for Knowledge Base Question Generation
authors: Guo Shasha, Liao Lizi, Zhang Jing, Wang Yanling, Li Cuiping, Chen Hong
conference: "Arxiv"
year: 2024
bibkey: guo2024sgsh
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.01923"}
tags: ['GPT', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'RAG', 'Tools', 'Training Techniques']
---
Knowledge base question generation (KBQG) aims to generate natural language questions from a set of triplet facts extracted from KB. Existing methods have significantly boosted the performance of KBQG via pre-trained language models (PLMs) thanks to the richly endowed semantic knowledge. With the advance of pre-training techniques large language models (LLMs) (e.g. GPT-3.5) undoubtedly possess much more semantic knowledge. Therefore how to effectively organize and exploit the abundant knowledge for KBQG becomes the focus of our study. In this work we propose SGSH--a simple and effective framework to Stimulate GPT-3.5 with Skeleton Heuristics to enhance KBQG. The framework incorporates skeleton heuristics which provides more fine-grained guidance associated with each input to stimulate LLMs to generate optimal questions encompassing essential elements like the question phrase and the auxiliary verb.More specifically we devise an automatic data construction strategy leveraging ChatGPT to construct a skeleton training dataset based on which we employ a soft prompting approach to train a BART model dedicated to generating the skeleton associated with each input. Subsequently skeleton heuristics are encoded into the prompt to incentivize GPT-3.5 to generate desired questions. Extensive experiments demonstrate that SGSH derives the new state-of-the-art performance on the KBQG tasks.
