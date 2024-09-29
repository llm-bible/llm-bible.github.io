---
layout: publication
title: 'Lion: Adversarial Distillation Of Proprietary Large Language Models'
authors: Jiang Yuxin, Chan Chunkit, Chen Mingyang, Wang Wei
conference: "Arxiv"
year: 2023
bibkey: jiang2023adversarial
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.12870"}
  - {name: "Code", url: "https://github.com/YJiangcm/Lion"}
tags: ['Attention Mechanism', 'Distillation', 'Efficiency And Optimization', 'GPT', 'Has Code', 'Model Architecture', 'Prompting', 'RAG', 'Reinforcement Learning', 'Security', 'Tools', 'Training Techniques']
---
The practice of transferring knowledge from a sophisticated proprietary large language model (LLM) to a compact open-source LLM has garnered considerable attention. Previous works have focused on a unidirectional knowledge distillation way by aligning the responses of the student model with those of the teacher model to a set of instructions. Nevertheless they overlooked the possibility of incorporating any reciprocal feedback--identifying challenging instructions where the student models performance falls short--to boost the student models proficiency iteratively. To this end we propose a novel adversarial distillation framework for a more efficient knowledge transfer. Leveraging the versatile role adaptability of LLMs we prompt the teacher model to identify hard instructions and generate new hard instructions for the student model creating a three-stage adversarial loop of imitation discrimination and generation. By applying this adversarial framework we successfully transfer knowledge from ChatGPT to a student model (named Lion) using a mere 70k training data. Our results show that Lion-13B not only achieves comparable open-ended generation capabilities to ChatGPT but surpasses conventional state-of-the-art (SOTA) instruction-tuned models like Vicuna-13B by 55.437; in challenging zero-shot reasoning benchmarks such as BIG-Bench Hard (BBH) and 16.737; on AGIEval. Code and model can be found at https://github.com/YJiangcm/Lion."
