---
layout: publication
title: Vi(E)va LLM! A Conceptual Stack for Evaluating and Interpreting Generative AI-based Visualizations
authors: Podo Luca, Ishmal Muhammad, Angelini Marco
conference: "Arxiv"
year: 2024
bibkey: podo2024vieva
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.02167"}
tags: ['ARXIV', 'GPT', 'LLM', 'Model Architecture', 'Reinforcement Learning', 'Tools']
---
The automatic generation of visualizations is an old task that through the years has shown more and more interest from the research and practitioner communities. Recently large language models (LLM) have become an interesting option for supporting generative tasks related to visualization demonstrating initial promising results. At the same time several pitfalls like the multiple ways of instructing an LLM to generate the desired result the different perspectives leading the generation (code-based image-based grammar-based) and the presence of hallucinations even for the visualization generation task make their usage less affordable than expected. Following similar initiatives for benchmarking LLMs this paper copes with the problem of modeling the evaluation of a generated visualization through an LLM. We propose a theoretical evaluation stack EvaLLM that decomposes the evaluation effort in its atomic components characterizes their nature and provides an overview of how to implement and interpret them. We also designed and implemented an evaluation platform that provides a benchmarking resource for the visualization generation task. The platform supports automatic and manual scoring conducted by multiple assessors to support a fine-grained and semantic evaluation based on the EvaLLM stack. Two case studies on GPT3.5-turbo with Code Interpreter and Llama2-70-b models show the benefits of EvaLLM and illustrate interesting results on the current state-of-the-art LLM-generated visualizations.
