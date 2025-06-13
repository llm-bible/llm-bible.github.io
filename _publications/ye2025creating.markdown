---
layout: publication
title: 'Mographgpt: Creating Interactive Scenes Using Modular LLM And Graphical Control'
authors: Hui Ye, Chufeng Xiao, Jiaye Leng, Pengfei Xu, Hongbo Fu
conference: "Arxiv"
year: 2025
bibkey: ye2025creating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.04983"}
tags: ['GPT', 'Model Architecture', 'Reinforcement Learning']
---
Creating interactive scenes often involves complex programming tasks.
Although large language models (LLMs) like ChatGPT can generate code from
natural language, their output is often error-prone, particularly when
scripting interactions among multiple elements. The linear conversational
structure limits the editing of individual elements, and lacking graphical and
precise control complicates visual integration. To address these issues, we
integrate an element-level modularization technique that processes textual
descriptions for individual elements through separate LLM modules, with a
central module managing interactions among elements. This modular approach
allows for refining each element independently. We design a graphical user
interface, MoGraphGPT , which combines modular LLMs with enhanced graphical
control to generate codes for 2D interactive scenes. It enables direct
integration of graphical information and offers quick, precise control through
automatically generated sliders. Our comparative evaluation against an AI
coding tool, Cursor Composer, as the baseline system and a usability study show
MoGraphGPT significantly improves easiness, controllability, and refinement in
creating complex 2D interactive scenes with multiple visual elements in a
coding-free manner.
