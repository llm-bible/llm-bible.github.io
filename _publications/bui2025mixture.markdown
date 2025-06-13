---
layout: publication
title: 'Mixture-of-personas Language Models For Population Simulation'
authors: Ngoc Bui, Hieu Trung Nguyen, Shantanu Kumar, Julian Theodore, Weikang Qiu, Viet Anh Nguyen, Rex Ying
conference: "Arxiv"
year: 2025
bibkey: bui2025mixture
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.05019'}
tags: ['Agentic', 'Training Techniques', 'Applications', 'Merging', 'Prompting']
---
Advances in Large Language Models (LLMs) paved the way for their emerging
applications in various domains, such as human behavior simulations, where LLMs
could augment human-generated data in social science research and machine
learning model training. However, pretrained LLMs often fail to capture the
behavioral diversity of target populations due to the inherent variability
across individuals and groups. To address this, we propose \textit\{Mixture of
Personas\} (MoP), a \textit\{probabilistic\} prompting method that aligns the LLM
responses with the target population. MoP is a contextual mixture model, where
each component is an LM agent characterized by a persona and an exemplar
representing subpopulation behaviors. The persona and exemplar are randomly
chosen according to the learned mixing weights to elicit diverse LLM responses
during simulation. MoP is flexible, requires no model finetuning, and is
transferable across base models. Experiments for synthetic data generation show
that MoP outperforms competing methods in alignment and diversity metrics.
