---
layout: publication
title: Vi(e)va LLM! A Conceptual Stack For Evaluating And Interpreting Generative Ai45;based Visualizations
authors: Podo Luca, Ishmal Muhammad, Angelini Marco
conference: "Arxiv"
year: 2024
bibkey: podo2024conceptual
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.02167"}
tags: ['Applications', 'GPT', 'Model Architecture', 'Reinforcement Learning', 'Tools']
---
The automatic generation of visualizations is an old task that through the years has shown more and more interest from the research and practitioner communities. Recently large language models (LLM) have become an interesting option for supporting generative tasks related to visualization demonstrating initial promising results. At the same time several pitfalls like the multiple ways of instructing an LLM to generate the desired result the different perspectives leading the generation (code45;based image45;based grammar45;based) and the presence of hallucinations even for the visualization generation task make their usage less affordable than expected. Following similar initiatives for benchmarking LLMs this paper copes with the problem of modeling the evaluation of a generated visualization through an LLM. We propose a theoretical evaluation stack EvaLLM that decomposes the evaluation effort in its atomic components characterizes their nature and provides an overview of how to implement and interpret them. We also designed and implemented an evaluation platform that provides a benchmarking resource for the visualization generation task. The platform supports automatic and manual scoring conducted by multiple assessors to support a fine45;grained and semantic evaluation based on the EvaLLM stack. Two case studies on GPT3.545;turbo with Code Interpreter and Llama245;7045;b models show the benefits of EvaLLM and illustrate interesting results on the current state45;of45;the45;art LLM45;generated visualizations.
