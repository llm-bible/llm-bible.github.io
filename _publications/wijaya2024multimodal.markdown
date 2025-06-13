---
layout: publication
title: 'Multimodal Preference Data Synthetic Alignment With Reward Model'
authors: Robert Wijaya, Ngoc-bao Nguyen, Ngai-man Cheung
conference: "Arxiv"
year: 2024
bibkey: wijaya2024multimodal
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2412.17417'}
tags: ['Efficiency and Optimization', 'GPT', 'Model Architecture', 'Training Techniques', 'Tools', 'Prompting', 'Applications', 'Multimodal Models', 'Reinforcement Learning', 'Pre-Training']
---
Multimodal large language models (MLLMs) have significantly advanced tasks
like caption generation and visual question answering by integrating visual and
textual data. However, they sometimes produce misleading or hallucinate content
due to discrepancies between their pre-training data and real user prompts.
Existing approaches using Direct Preference Optimization (DPO) in
vision-language tasks often rely on strong models like GPT-4 or CLIP to
determine positive and negative responses. Here, we propose a new framework in
generating synthetic data using a reward model as a proxy of human preference
for effective multimodal alignment with DPO training. The resulting DPO dataset
ranges from 2K to 9K image-text pairs, was evaluated on LLaVA-v1.5-7B, where
our approach demonstrated substantial improvements in both the trustworthiness
and reasoning capabilities of the base model across multiple hallucination and
vision-language benchmark. The experiment results indicate that integrating
selected synthetic data, such as from generative and rewards models can
effectively reduce reliance on human-annotated data while enhancing MLLMs'
alignment capability, offering a scalable solution for safer deployment.
