---
layout: publication
title: 'Alexpaca: Learning Factual Clarification Question Generation Without Examples'
authors: Matthew Toles, Yukun Huang, Zhou Yu, Luis Gravano
conference: "Arxiv"
year: 2023
bibkey: toles2023learning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.11571"}
tags: ['Training Techniques', 'Model Architecture', 'Reinforcement Learning', 'GPT', 'Pretraining Methods', 'Fine-Tuning']
---
Real-life tasks such as giving legal or technical advice often lack complete
context at the outset and can have disparate answers depending thereon. The
ability to derive missing factual information by asking clarifying questions
(ACQ) is an important element of real-life collaboration on such reasoning
tasks. Existing factual clarification question challenges evaluate generations
based on word overlap or human evaluations. Recent work explores generating a
response to the clarifying question then evaluating its utility directly. So
far, these tasks are limited to disambiguating the user's intent rather than
concrete facts about the situation. The factual domain presents unique
challenges since responses to clarification questions must be factually true
for accurate evaluation. To enable evaluation of factual domain clarification
question generation, We present a new task that focuses on the ability to
elicit missing information in multi-hop reasoning tasks. The task,
HotpotQA-FLM, can be evaluated automatically, making it convenient for
benchmarking language models. We observe that humans outperform GPT-4 by a
large margin, while Llama 3 8B Instruct does not even beat the dummy baseline
in some metrics. Finally, we find by fine-tuning Llama 3 8B Instruct on its own
generations, filtered via rejection sampling, we can improve information
recovery by 27.6 percent.
