---
layout: publication
title: 'IAP: Improving Continual Learning Of Vision-language Models Via Instance-aware Prompting'
authors: Hao Fu, Hanbin Zhao, Jiahua Dong, Chao Zhang, Hui Qian
conference: "Arxiv"
year: 2025
bibkey: fu2025improving
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.20612"}
  - {name: "Code", url: "https://github.com/FerdinandZJU/IAP"}
tags: ['Fine-Tuning', 'Transformer', 'Tools', 'Model Architecture', 'Training Techniques', 'Has Code', 'Pretraining Methods', 'Multimodal Models', 'Prompting']
---
Recent pre-trained vision-language models (PT-VLMs) often face a Multi-Domain
Class-Incremental Learning (MCIL) scenario in practice, where several classes
and domains of multi-modal tasks are incrementally arrived. Without access to
previously learned tasks and unseen tasks, memory-constrained MCIL suffers from
forward and backward forgetting. To alleviate the above challenges,
parameter-efficient fine-tuning techniques (PEFT), such as prompt tuning, are
employed to adapt the PT-VLM to the diverse incrementally learned tasks. To
achieve effective new task adaptation, existing methods only consider the
effect of PEFT strategy selection, but neglect the influence of PEFT parameter
setting (e.g., prompting). In this paper, we tackle the challenge of optimizing
prompt designs for diverse tasks in MCIL and propose an Instance-Aware
Prompting (IAP) framework. Specifically, our Instance-Aware Gated Prompting
(IA-GP) module enhances adaptation to new tasks while mitigating forgetting by
dynamically assigning prompts across transformer layers at the instance level.
Our Instance-Aware Class-Distribution-Driven Prompting (IA-CDDP) improves the
task adaptation process by determining an accurate task-label-related
confidence score for each instance. Experimental evaluations across 11
datasets, using three performance metrics, demonstrate the effectiveness of our
proposed method. Code can be found at https://github.com/FerdinandZJU/IAP.
