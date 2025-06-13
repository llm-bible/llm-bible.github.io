---
layout: publication
title: 'Safe To Serve: Aligning Instruction-tuned Models For Safety And Helpfulness'
authors: Avinash Amballa, Durga Sandeep Saluru, Gayathri Akkinapalli, Abhishek Sureddy, Akshay Kumar Sureddy
conference: "Arxiv"
year: 2024
bibkey: amballa2024safe
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.00074"}
tags: ['Fine-Tuning', 'Responsible AI', 'Tools', 'Efficiency and Optimization', 'Ethics and Bias', 'Applications', 'RAG', 'Language Modeling', 'Reinforcement Learning', 'Prompting']
---
Large language models (LLMs) have demonstrated remarkable capabilities in
complex reasoning and text generation. However, these models can inadvertently
generate unsafe or biased responses when prompted with problematic inputs,
raising significant ethical and practical concerns for real-world deployment.
This research addresses the critical challenge of developing language models
that generate both helpful and harmless content, navigating the delicate
balance between model performance and safety. We demonstrate that incorporating
safety-related instructions during the instruction-tuning of pre-trained models
significantly reduces toxic responses to unsafe prompts without compromising
performance on helpfulness datasets. We found Direct Preference Optimization
(DPO) to be particularly effective, outperforming both SIT and RAFT by
leveraging both chosen and rejected responses for learning. Our approach
increased safe responses from 40\\(%\\) to over 90\\(%\\) across various harmfulness
benchmarks. In addition, we discuss a rigorous evaluation framework
encompassing specialized metrics and diverse datasets for safety and
helpfulness tasks ensuring a comprehensive assessment of the model's
capabilities.
