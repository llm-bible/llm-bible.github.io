---
layout: publication
title: 'Dr-llava: Visual Instruction Tuning With Symbolic Clinical Grounding'
authors: Sun Shenghuan, Goldgof Gregory M., Schubert Alexander, Sun Zhiqing, Hartvigsen Thomas, Butte Atul J., Alaa Ahmed
conference: "Arxiv"
year: 2024
bibkey: sun2024dr
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.19567"}
tags: ['Agentic', 'GPT', 'Model Architecture', 'Multimodal Models', 'Reinforcement Learning', 'Training Techniques']
---
Vision-Language Models (VLM) can support clinicians by analyzing medical images and engaging in natural language interactions to assist in diagnostic and treatment tasks. However, VLMs often exhibit hallucinogenic behavior, generating textual outputs not grounded in contextual multimodal information. This challenge is particularly pronounced in the medical domain, where we do not only require VLM outputs to be accurate in single interactions but also to be consistent with clinical reasoning and diagnostic pathways throughout multi-turn conversations. For this purpose, we propose a new alignment algorithm that uses symbolic representations of clinical reasoning to ground VLMs in medical knowledge. These representations are utilized to (i) generate GPT-4-guided visual instruction tuning data at scale, simulating clinician-VLM conversations with demonstrations of clinical reasoning, and (ii) create an automatic reward function that evaluates the clinical validity of VLM generations throughout clinician-VLM interactions. Our algorithm eliminates the need for human involvement in training data generation or reward model construction, reducing costs compared to standard reinforcement learning with human feedback (RLHF). We apply our alignment algorithm to develop Dr-LLaVA, a conversational VLM finetuned for analyzing bone marrow pathology slides, demonstrating strong performance in multi-turn medical conversations.
