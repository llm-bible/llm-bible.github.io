---
layout: publication
title: 'Tulu 3: Pushing Frontiers In Open Language Model Post-training'
authors: Nathan Lambert, Jacob Morrison, Valentina Pyatkin, Shengyi Huang, Hamish Ivison, Faeze Brahman, Lester James V. Miranda, Alisa Liu, Nouha Dziri, Shane Lyu, Yuling Gu, Saumya Malik, Victoria Graf, Jena D. Hwang, Jiangjiang Yang, Ronan Le Bras, Oyvind Tafjord, Chris Wilhelm, Luca Soldaini, Noah A. Smith, Yizhong Wang, Pradeep Dasigi, Hannaneh Hajishirzi
conference: "Arxiv"
year: 2024
bibkey: lambert2024tulu
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2411.15124'}
tags: ['Agentic', 'Efficiency and Optimization', 'GPT', 'Training Techniques', 'Model Architecture', 'Fine-Tuning', 'Reinforcement Learning', 'Ethics and Bias', 'Interpretability']
---
Language model post-training is applied to refine behaviors and unlock new
skills across a wide range of recent language models, but open recipes for
applying these techniques lag behind proprietary ones. The underlying training
data and recipes for post-training are simultaneously the most important pieces
of the puzzle and the portion with the least transparency. To bridge this gap,
we introduce Tulu 3, a family of fully-open state-of-the-art post-trained
models, alongside its data, code, and training recipes, serving as a
comprehensive guide for modern post-training techniques. Tulu 3, which builds
on Llama 3.1 base models, achieves results surpassing the instruct versions of
Llama 3.1, Qwen 2.5, Mistral, and even closed models such as GPT-4o-mini and
Claude 3.5-Haiku. The training algorithms for our models include supervised
finetuning (SFT), Direct Preference Optimization (DPO), and a novel method we
call Reinforcement Learning with Verifiable Rewards (RLVR). With Tulu 3, we
introduce a multi-task evaluation scheme for post-training recipes with
development and unseen evaluations, standard benchmark implementations, and
substantial decontamination of existing open datasets on said benchmarks. We
conclude with analysis and discussion of training methods that did not reliably
improve performance.
  In addition to the Tulu 3 model weights and demo, we release the complete
recipe -- including datasets for diverse core skills, a robust toolkit for data
curation and evaluation, the training code and infrastructure, and, most
importantly, a detailed report for reproducing and further adapting the Tulu 3
approach to more domains.
