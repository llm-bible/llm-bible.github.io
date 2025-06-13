---
layout: publication
title: 'Automated Code Generation For Information Technology Tasks In YAML Through Large Language Models'
authors: Saurabh Pujar, Luca Buratti, Xiaojie Guo, Nicolas Dupuis, Burn Lewis, Sahil Suneja, Atin Sood, Ganesh Nalawade, Matthew Jones, Alessandro Morari, Ruchir Puri
conference: "Arxiv"
year: 2023
bibkey: pujar2023automated
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2305.02783'}
tags: ['Attention Mechanism', 'Transformer', 'Few-Shot', 'Training Techniques', 'Model Architecture', 'Tools', 'Prompting', 'Applications', 'Pretraining Methods']
---
The recent improvement in code generation capabilities due to the use of
large language models has mainly benefited general purpose programming
languages. Domain specific languages, such as the ones used for IT Automation,
have received far less attention, despite involving many active developers and
being an essential component of modern cloud platforms. This work focuses on
the generation of Ansible-YAML, a widely used markup language for IT
Automation. We present Ansible Wisdom, a natural-language to Ansible-YAML code
generation tool, aimed at improving IT automation productivity. Ansible Wisdom
is a transformer-based model, extended by training with a new dataset
containing Ansible-YAML. We also develop two novel performance metrics for YAML
and Ansible to capture the specific characteristics of this domain. Results
show that Ansible Wisdom can accurately generate Ansible script from natural
language prompts with performance comparable or better than existing state of
the art code generation models. In few-shot settings we asses the impact of
training with Ansible, YAML data and compare with different baselines including
Codex-Davinci-002. We also show that after finetuning, our Ansible specific
model (BLEU: 66.67) can outperform a much larger Codex-Davinci-002 (BLEU: 50.4)
model, which was evaluated in few shot settings.
