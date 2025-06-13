---
layout: publication
title: 'Text2model: Generating Dynamic Chemical Reactor Models Using Large Language Models (llms)'
authors: Sophia Rupprecht, Yassine Hounat, Monisha Kumar, Giacomo Lastrucci, Artur M. Schweidtmann
conference: "Arxiv"
year: 2025
bibkey: rupprecht2025generating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.17004"}
tags: ['Model Architecture', 'GPT']
---
As large language models have shown remarkable capabilities in conversing via
natural language, the question arises as to how LLMs could potentially assist
chemical engineers in research and industry with domain-specific tasks. We
generate dynamic chemical reactor models in Modelica code format from textual
descriptions as user input. We fine-tune Llama 3.1 8B Instruct on synthetically
generated Modelica code for different reactor scenarios. We compare the
performance of our fine-tuned model to the baseline Llama 3.1 8B Instruct model
and GPT4o. We manually assess the models' predictions regarding the syntactic
and semantic accuracy of the generated dynamic models. We find that
considerable improvements are achieved by the fine-tuned model with respect to
both the semantic and the syntactic accuracy of the Modelica models. However,
the fine-tuned model lacks a satisfactory ability to generalize to unseen
scenarios compared to GPT4o.
