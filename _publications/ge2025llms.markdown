---
layout: publication
title: 'Llms Are Vulnerable To Malicious Prompts Disguised As Scientific Language'
authors: Yubin Ge, Neeraja Kirtane, Hao Peng, Dilek Hakkani-tür
conference: "Arxiv"
year: 2025
bibkey: ge2025llms
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2501.14073'}
tags: ['Training Techniques', 'Model Architecture', 'GPT', 'Prompting', 'Reinforcement Learning', 'Ethics and Bias', 'Responsible AI']
---
As large language models (LLMs) have been deployed in various real-world
settings, concerns about the harm they may propagate have grown. Various
jailbreaking techniques have been developed to expose the vulnerabilities of
these models and improve their safety. This work reveals that many
state-of-the-art LLMs are vulnerable to malicious requests hidden behind
scientific language. Specifically, our experiments with GPT4o, GPT4o-mini,
GPT-4, LLama3-405B-Instruct, Llama3-70B-Instruct, Cohere, Gemini models
demonstrate that, the models' biases and toxicity substantially increase when
prompted with requests that deliberately misinterpret social science and
psychological studies as evidence supporting the benefits of stereotypical
biases. Alarmingly, these models can also be manipulated to generate fabricated
scientific arguments claiming that biases are beneficial, which can be used by
ill-intended actors to systematically jailbreak these strong LLMs. Our analysis
studies various factors that contribute to the models' vulnerabilities to
malicious requests in academic language. Mentioning author names and venues
enhances the persuasiveness of models, and the bias scores increase as
dialogues progress. Our findings call for a more careful investigation on the
use of scientific data for training LLMs.
