---
layout: publication
title: 'Reasoning Llms For User-aware Multimodal Conversational Agents'
authors: Hamed Rahimi, Jeanne Cattoni, Meriem Beghili, Mouad Abrini, Mahdi Khoramshahi, Maribel Pino, Mohamed Chetouani
conference: "Arxiv"
year: 2025
bibkey: rahimi2025reasoning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.01700"}
tags: ['Agentic', 'Tools', 'Ethics and Bias', 'RAG', 'Bias Mitigation', 'Model Architecture', 'Reinforcement Learning', 'Multimodal Models']
---
Personalization in social robotics is critical for fostering effective
human-robot interactions, yet systems often face the cold start problem, where
initial user preferences or characteristics are unavailable. This paper
proposes a novel framework called USER-LLM R1 for a user-aware conversational
agent that addresses this challenge through dynamic user profiling and model
initiation. Our approach integrates chain-of-thought (CoT) reasoning models to
iteratively infer user preferences and vision-language models (VLMs) to
initialize user profiles from multimodal inputs, enabling personalized
interactions from the first encounter. Leveraging a Retrieval-Augmented
Generation (RAG) architecture, the system dynamically refines user
representations within an inherent CoT process, ensuring contextually relevant
and adaptive responses. Evaluations on the ElderlyTech-VQA Bench demonstrate
significant improvements in ROUGE-1 (+23.2%), ROUGE-2 (+0.6%), and ROUGE-L
(+8%) F1 scores over state-of-the-art baselines, with ablation studies
underscoring the impact of reasoning model size on performance. Human
evaluations further validate the framework's efficacy, particularly for elderly
users, where tailored responses enhance engagement and trust. Ethical
considerations, including privacy preservation and bias mitigation, are
rigorously discussed and addressed to ensure responsible deployment.
