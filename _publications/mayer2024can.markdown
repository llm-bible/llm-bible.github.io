---
layout: publication
title: Can OpenSource beat ChatGPT -- A Comparative Study of Large Language Models for Text-to-Code Generation
authors: Mayer Luis, Heumann Christian, Aßenmacher Matthias
conference: "Arxiv"
year: 2024
bibkey: mayer2024can
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.04164"}
tags: ['ARXIV', 'Applications', 'Chatgpt', 'GPT', 'LLM', 'Tools']
---
In recent years large language models (LLMs) have emerged as powerful tools with potential applications in various fields including software engineering. Within the scope of this research we evaluate five different state-of-the-art LLMs - Bard BingChat ChatGPT Llama2 and Code Llama - concerning their capabilities for text-to-code generation. In an empirical study we feed prompts with textual descriptions of coding problems sourced from the programming website LeetCode to the models with the task of creating solutions in Python. Subsequently the quality of the generated outputs is assessed using the testing functionalities of LeetCode. The results indicate large differences in performance between the investigated models. ChatGPT can handle these typical programming challenges by far the most effectively surpassing even code-specialized models like Code Llama. To gain further insights we measure the runtime as well as the memory usage of the generated outputs and compared them to the other code submissions on Leetcode. A detailed error analysis encompassing a comparison of the differences concerning correct indentation and form of the generated code as well as an assignment of the incorrectly solved tasks to certain error categories allows us to obtain a more nuanced picture of the results and potential for improvement. The results also show a clear pattern of increasingly incorrect produced code when the models are facing a lot of context in the form of longer prompts.
