---
layout: publication
title: COCO Is ALL You Need For Visual Instruction Fine45;tuning
authors: Han Xiaotian, Wang Yiqi, Zhai Bohan, You Quanzeng, Yang Hongxia
conference: "Arxiv"
year: 2024
bibkey: han2024coco
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.08968"}
tags: ['Efficiency And Optimization', 'GPT', 'Model Architecture', 'Reinforcement Learning']
---
Multi45;modal Large Language Models (MLLMs) are increasingly prominent in the field of artificial intelligence. Visual instruction fine45;tuning (IFT) is a vital process for aligning MLLMs output with users intentions. High45;quality and diversified instruction following data is the key to this fine45;tuning process. Recent studies propose to construct visual IFT datasets through a multifaceted approach transforming existing datasets with rule45;based templates employing GPT45;4 for rewriting annotations and utilizing GPT45;4V for visual dataset pseudo45;labeling. LLaVA45;1.5 adopted similar approach and construct LLaVA45;mix45;665k which is one of the simplest most widely used yet most effective IFT datasets today. Notably when properly fine45;tuned with this dataset MLLMs can achieve state45;of45;the45;art performance on several benchmarks. However we noticed that models trained with this dataset often struggle to follow user instructions properly in multi45;round dialog. In addition tradition caption and VQA evaluation benchmarks with their closed45;form evaluation structure are not fully equipped to assess the capabilities of modern open45;ended generative MLLMs. This problem is not unique to the LLaVA45;mix45;665k dataset but may be a potential issue in all IFT datasets constructed from image captioning or VQA sources though the extent of this issue may vary. We argue that datasets with diverse and high45;quality detailed instruction following annotations are essential and adequate for MLLMs IFT. In this work we establish a new IFT dataset with images sourced from the COCO dataset along with more diverse instructions. Our experiments show that when fine45;tuned with out proposed dataset MLLMs achieve better performance on open45;ended evaluation benchmarks in both single45;round and multi45;round dialog setting.
