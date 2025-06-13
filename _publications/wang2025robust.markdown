---
layout: publication
title: 'Robust Few-shot Vision-language Model Adaptation'
authors: Hanxin Wang, Tian Liu, Shu Kong
conference: "Arxiv"
year: 2025
bibkey: wang2025robust
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2506.04713'}
tags: ['Few-Shot', 'Efficiency and Optimization', 'Security', 'Training Techniques', 'Prompting', 'Fine-Tuning', 'Multimodal Models', 'Pretraining Methods']
---
Pretrained VLMs achieve strong performance on downstream tasks when adapted with just a few labeled examples. As the adapted models inevitably encounter out-of-distribution (OOD) test data that deviates from the in-distribution (ID) task-specific training data, enhancing OOD generalization in few-shot adaptation is critically important. We study robust few-shot VLM adaptation, aiming to increase both ID and OOD accuracy. By comparing different adaptation methods (e.g., prompt tuning, linear probing, contrastive finetuning, and full finetuning), we uncover three key findings: (1) finetuning with proper hyperparameters significantly outperforms the popular VLM adaptation methods prompt tuning and linear probing; (2) visual encoder-only finetuning achieves better efficiency and accuracy than contrastively finetuning both visual and textual encoders; (3) finetuning the top layers of the visual encoder provides the best balance between ID and OOD accuracy. Building on these findings, we propose partial finetuning of the visual encoder empowered with two simple augmentation techniques: (1) retrieval augmentation which retrieves task-relevant data from the VLM's pretraining dataset to enhance adaptation, and (2) adversarial perturbation which promotes robustness during finetuning. Results show that the former/latter boosts OOD/ID accuracy while slightly sacrificing the ID/OOD accuracy. Yet, perhaps understandably, naively combining the two does not maintain their best OOD/ID accuracy. We address this dilemma with the developed SRAPF, Stage-wise Retrieval Augmentation-based Adversarial Partial Finetuning. SRAPF consists of two stages: (1) partial finetuning the visual encoder using both ID and retrieved data, and (2) adversarial partial finetuning with few-shot ID data. Extensive experiments demonstrate that SRAPF achieves the state-of-the-art ID and OOD accuracy on the ImageNet OOD benchmarks.
