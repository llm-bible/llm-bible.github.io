---
layout: publication
title: 'Code Prompting Elicits Conditional Reasoning Abilities In Text+code Llms'
authors: Puerto Haritz, Tutek Martin, Aditya Somak, Zhu Xiaodan, Gurevych Iryna
conference: "Arxiv"
year: 2024
bibkey: puerto2024code
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.10065"}
tags: ['Efficiency And Optimization', 'GPT', 'In Context Learning', 'Model Architecture', 'Prompting', 'Reinforcement Learning']
---
Reasoning is a fundamental component of language understanding. Recent prompting techniques, such as chain of thought, have consistently improved LLMs' performance on various reasoning tasks. Nevertheless, there is still little understanding of what triggers reasoning abilities in LLMs in the inference stage. In this paper, we introduce code prompting, a chain of prompts that transforms a natural language problem into code and directly prompts the LLM using the generated code without resorting to external code execution. We hypothesize that code prompts can elicit certain reasoning capabilities of LLMs trained on text and code and utilize the proposed method to improve conditional reasoning, the ability to infer different conclusions depending on the fulfillment of certain conditions. We find that code prompting exhibits a high-performance boost for multiple LLMs (up to 22.52 percentage points on GPT 3.5, 7.75 on Mixtral, and 16.78 on Mistral) across multiple conditional reasoning datasets. We then conduct comprehensive experiments to understand how code prompts trigger reasoning abilities and which capabilities are elicited in the underlying models. Our analysis of GPT 3.5 reveals that the code formatting of the input problem is essential for performance improvement. Furthermore, code prompts improve sample efficiency of in-context learning and facilitate state tracking of variables or entities.
