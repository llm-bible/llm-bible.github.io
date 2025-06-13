---
layout: publication
title: 'Improved Large Language Model Jailbreak Detection Via Pretrained Embeddings'
authors: Erick Galinkin, Martin Sablotny
conference: "Arxiv"
year: 2024
bibkey: galinkin2024improved
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2412.01547'}
tags: ['Agentic', 'Security', 'Training Techniques', 'Applications', 'Tools', 'Prompting', 'Responsible AI']
---
The adoption of large language models (LLMs) in many applications, from
customer service chat bots and software development assistants to more capable
agentic systems necessitates research into how to secure these systems. Attacks
like prompt injection and jailbreaking attempt to elicit responses and actions
from these models that are not compliant with the safety, privacy, or content
policies of organizations using the model in their application. In order to
counter abuse of LLMs for generating potentially harmful replies or taking
undesirable actions, LLM owners must apply safeguards during training and
integrate additional tools to block the LLM from generating text that abuses
the model. Jailbreaking prompts play a vital role in convincing an LLM to
generate potentially harmful content, making it important to identify
jailbreaking attempts to block any further steps. In this work, we propose a
novel approach to detect jailbreak prompts based on pairing text embeddings
well-suited for retrieval with traditional machine learning classification
algorithms. Our approach outperforms all publicly available methods from open
source LLM security applications.
