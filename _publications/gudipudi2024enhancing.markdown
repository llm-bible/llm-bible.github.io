---
layout: publication
title: 'Enhancing AI Safety Through The Fusion Of Low Rank Adapters'
authors: Satya Swaroop Gudipudi, Sreeram Vipparla, Harpreet Singh, Shashwat Goel, Ponnurangam Kumaraguru
conference: "Arxiv"
year: 2024
bibkey: gudipudi2024enhancing
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2501.06208'}
tags: ['RAG', 'Training Techniques', 'Merging', 'Fine-Tuning', 'Prompting', 'Responsible AI', 'Pretraining Methods']
---
Instruction fine-tuning of large language models (LLMs) is a powerful method
for improving task-specific performance, but it can inadvertently lead to a
phenomenon where models generate harmful responses when faced with malicious
prompts. In this paper, we explore Low-Rank Adapter Fusion (LoRA) as a means to
mitigate these risks while preserving the model's ability to handle diverse
instructions effectively. Through an extensive comparative analysis against
established baselines using recognized benchmark datasets, we demonstrate a
42% reduction in the harmfulness rate by leveraging LoRA fusion between a task
adapter and a safety adapter, the latter of which is specifically trained on
our safety dataset. However, we also observe exaggerated safety behaviour,
where the model rejects safe prompts that closely resemble unsafe ones
