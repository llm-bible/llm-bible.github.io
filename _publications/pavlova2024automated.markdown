---
layout: publication
title: 'Automated Red Teaming With GOAT: The Generative Offensive Agent Tester'
authors: Maya Pavlova, Erik Brinkman, Krithika Iyer, Vitor Albiero, Joanna Bitton, Hailey Nguyen, Joe Li, Cristian Canton Ferrer, Ivan Evtimov, Aaron Grattafiori
conference: "Arxiv"
year: 2024
bibkey: pavlova2024automated
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.01606"}
tags: ['Responsible AI', 'Agentic', 'GPT', 'RAG', 'Model Architecture', 'Security', 'Training Techniques', 'Prompting']
---
Red teaming assesses how large language models (LLMs) can produce content
that violates norms, policies, and rules set during their safety training.
However, most existing automated methods in the literature are not
representative of the way humans tend to interact with AI models. Common users
of AI models may not have advanced knowledge of adversarial machine learning
methods or access to model internals, and they do not spend a lot of time
crafting a single highly effective adversarial prompt. Instead, they are likely
to make use of techniques commonly shared online and exploit the multiturn
conversational nature of LLMs. While manual testing addresses this gap, it is
an inefficient and often expensive process. To address these limitations, we
introduce the Generative Offensive Agent Tester (GOAT), an automated agentic
red teaming system that simulates plain language adversarial conversations
while leveraging multiple adversarial prompting techniques to identify
vulnerabilities in LLMs. We instantiate GOAT with 7 red teaming attacks by
prompting a general-purpose model in a way that encourages reasoning through
the choices of methods available, the current target model's response, and the
next steps. Our approach is designed to be extensible and efficient, allowing
human testers to focus on exploring new areas of risk while automation covers
the scaled adversarial stress-testing of known risk territory. We present the
design and evaluation of GOAT, demonstrating its effectiveness in identifying
vulnerabilities in state-of-the-art LLMs, with an ASR@10 of 97% against Llama
3.1 and 88% against GPT-4 on the JailbreakBench dataset.
