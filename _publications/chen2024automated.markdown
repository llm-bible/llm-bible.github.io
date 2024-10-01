---
layout: publication
title: 'Automated Data Curation For Robust Language Model Fine-tuning'
authors: Chen Jiuhai, Mueller Jonas
conference: "Arxiv"
year: 2024
bibkey: chen2024automated
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.12776"}
tags: ['Applications', 'Fine Tuning', 'GPT', 'Language Modeling', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
"Large Language Models have become the de facto approach to sequence-to-sequence text generation tasks, but for specialized tasks/domains, a pretrained LLM lacks specific capabilities to produce accurate or well-formatted responses. Supervised fine-tuning specializes a LLM by training it on dataset of example prompts with target responses, but real-world data tends to be noisy. While many fine-tuning algorithms exist, here we consider a \emph\{data-centric AI\} perspective on LLM fine-tuning, studying how to \emph\{systematically\} curate the training dataset to improve the LLM produced via \emph\{any\} fine-tuning algorithm. We introduce an automated data curation pipeline CLEAR (Confidence-based LLM Evaluation And Rectification) for instruction tuning datasets, that can be used with any LLM and fine-tuning procedure. CLEAR estimates which training data is low-quality and either filters or corrects it. Automatically identifying which data to filter or correct is done via LLM-derived confidence estimates, to ensure only confident modifications to the dataset. Unlike existing data curation techniques, CLEAR is a comprehensive framework that can improve a dataset (and trained model outputs) without additional fine-tuning computations. We don't assume access to a stronger LLM than the model being fine-tuned (e.g.\ relying on GPT-4 when fine-tuning GPT-3.5), to see whether CLEAR can meaningfully improve the capabilities of any LLM. Experiments reveal that CLEAR consistently improves the performance of fine-tuned models across many datasets and models (like GPT-3.5 and Llama2)."
