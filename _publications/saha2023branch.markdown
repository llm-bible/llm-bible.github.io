---
layout: publication
title: Branch45;solve45;merge Improves Large Language Model Evaluation And Generation
authors: Saha Swarnadeep, Levy Omer, Celikyilmaz Asli, Bansal Mohit, Weston Jason, Li Xian
conference: "Arxiv"
year: 2023
bibkey: saha2023branch
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.15123"}
tags: ['Applications', 'Ethics And Bias', 'GPT', 'Language Modeling', 'Model Architecture', 'Prompting']
---
Large Language Models (LLMs) are frequently used for multi45;faceted language generation and evaluation tasks that involve satisfying intricate user constraints or taking into account multiple aspects and criteria. However their performance can fall short due to the models lack of coherence and inability to plan and decompose the problem. We propose Branch45;Solve45;Merge (BSM) a Large Language Model program (Schlag et al. 2023) for tackling such challenging natural language tasks. It consists of branch solve and merge modules that are parameterized with specific prompts to the base LLM. These three modules plan a decomposition of the task into multiple parallel sub45;tasks independently solve them and fuse the solutions to the sub45;tasks. We apply our method to the tasks of LLM response evaluation and constrained text generation and evaluate its effectiveness with multiple LLMs including Vicuna LLaMA45;245;chat and GPT45;4. BSM improves the evaluation correctness and consistency for each LLM by enhancing human45;LLM agreement by up to 2637; reducing length and pairwise position biases by up to 5037; and allowing LLaMA245;chat to match or outperform GPT45;4 on most domains. On a constraint story generation task BSM improves the coherence of stories while also improving constraint satisfaction by 1237;.
