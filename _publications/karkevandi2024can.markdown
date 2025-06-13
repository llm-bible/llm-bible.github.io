---
layout: publication
title: 'Can Reinforcement Learning Unlock The Hidden Dangers In Aligned Large Language Models?'
authors: Mohammad Bahrami Karkevandi, Nishant Vishwamitra, Peyman Najafirad
conference: "Arxiv"
year: 2024
bibkey: karkevandi2024can
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.02651"}
tags: ['Responsible AI', 'Agentic', 'Tools', 'RAG', 'Model Architecture', 'Reinforcement Learning', 'Security', 'Training Techniques', 'BERT', 'Prompting']
---
Large Language Models (LLMs) have demonstrated impressive capabilities in
natural language tasks, but their safety and morality remain contentious due to
their training on internet text corpora. To address these concerns, alignment
techniques have been developed to improve the public usability and safety of
LLMs. Yet, the potential for generating harmful content through these models
seems to persist. This paper explores the concept of jailbreaking
LLMs-reversing their alignment through adversarial triggers. Previous methods,
such as soft embedding prompts, manually crafted prompts, and gradient-based
automatic prompts, have had limited success on black-box models due to their
requirements for model access and for producing a low variety of manually
crafted prompts, making them susceptible to being blocked. This paper
introduces a novel approach using reinforcement learning to optimize
adversarial triggers, requiring only inference API access to the target model
and a small surrogate model. Our method, which leverages a BERTScore-based
reward function, enhances the transferability and effectiveness of adversarial
triggers on new black-box models. We demonstrate that this approach improves
the performance of adversarial triggers on a previously untested language
model.
