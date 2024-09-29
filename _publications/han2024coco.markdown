---
layout: publication
title: COCO Is "ALL'' You Need For Visual Instruction Fine-tuning
authors: Han Xiaotian, Wang Yiqi, Zhai Bohan, You Quanzeng, Yang Hongxia
conference: "Arxiv"
year: 2024
bibkey: han2024coco
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.08968"}
tags: ['Fine Tuning', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques']
---
Multi-modal Large Language Models (MLLMs) are increasingly prominent in the field of artificial intelligence. Visual instruction fine-tuning (IFT) is a vital process for aligning MLLMs output with users intentions. High-quality and diversified instruction following data is the key to this fine-tuning process. Recent studies propose to construct visual IFT datasets through a multifaceted approach transforming existing datasets with rule-based templates employing GPT-4 for rewriting annotations and utilizing GPT-4V for visual dataset pseudo-labeling. LLaVA-1.5 adopted similar approach and construct LLaVA-mix-665k which is one of the simplest most widely used yet most effective IFT datasets today. Notably when properly fine-tuned with this dataset MLLMs can achieve state-of-the-art performance on several benchmarks. However we noticed that models trained with this dataset often struggle to follow user instructions properly in multi-round dialog. In addition tradition caption and VQA evaluation benchmarks with their closed-form evaluation structure are not fully equipped to assess the capabilities of modern open-ended generative MLLMs. This problem is not unique to the LLaVA-mix-665k dataset but may be a potential issue in all IFT datasets constructed from image captioning or VQA sources though the extent of this issue may vary. We argue that datasets with diverse and high-quality detailed instruction following annotations are essential and adequate for MLLMs IFT. In this work we establish a new IFT dataset with images sourced from the COCO dataset along with more diverse instructions. Our experiments show that when fine-tuned with out proposed dataset MLLMs achieve better performance on open-ended evaluation benchmarks in both single-round and multi-round dialog setting.
