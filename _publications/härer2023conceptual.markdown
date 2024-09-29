---
layout: publication
title: 'Conceptual Model Interpreter For Large Language Models'
authors: Härer Felix
conference: "Arxiv"
year: 2023
bibkey: härer2023conceptual
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.07605"}
tags: ['Applications', 'Fine Tuning', 'GPT', 'Model Architecture', 'RAG', 'Reinforcement Learning', 'Tools']
---
Large Language Models (LLMs) recently demonstrated capabilities for generating source code in common programming languages. Additionally commercial products such as ChatGPT 4 started to provide code interpreters allowing for the automatic execution of generated code fragments instant feedback and the possibility to develop and refine in a conversational fashion. With an exploratory research approach this paper applies code generation and interpretation to conceptual models. The concept and prototype of a conceptual model interpreter is explored capable of rendering visual models generated in textual syntax by state-of-the-art LLMs such as Llama~2 and ChatGPT 4. In particular these LLMs can generate textual syntax for the PlantUML and Graphviz modeling software that is automatically rendered within a conversational user interface. The first result is an architecture describing the components necessary to interact with interpreters and LLMs through APIs or locally providing support for many commercial and open source LLMs and interpreters. Secondly experimental results for models generated with ChatGPT 4 and Llama 2 are discussed in two cases covering UML and on an instance level graphs created from custom data. The results indicate the possibility of modeling iteratively in a conversational fashion.
