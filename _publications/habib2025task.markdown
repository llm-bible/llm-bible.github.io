---
layout: publication
title: 'Reqbrain: Task-specific Instruction Tuning Of Llms For Ai-assisted Requirements Generation'
authors: Mohammad Kasra Habib, Daniel Graziotin, Stefan Wagner
conference: "Arxiv"
year: 2025
bibkey: habib2025task
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.17632"}
tags: ['BERT', 'Model Architecture', 'Merging', 'Reinforcement Learning']
---
Requirements elicitation and specification remains a labor-intensive, manual process prone to inconsistencies and gaps, presenting a significant challenge in modern software engineering. Emerging studies underscore the potential of employing large language models (LLMs) for automated requirements generation to support requirements elicitation and specification; however, it remains unclear how to implement this effectively. In this work, we introduce ReqBrain, an Al-assisted tool that employs a fine-tuned LLM to generate authentic and adequate software requirements. Software engineers can engage with ReqBrain through chat-based sessions to automatically generate software requirements and categorize them by type. We curated a high-quality dataset of ISO 29148-compliant requirements and fine-tuned five 7B-parameter LLMs to determine the most effective base model for ReqBrain. The top-performing model, Zephyr-7b-beta, achieved 89.30% Fl using the BERT score and a FRUGAL score of 91.20 in generating authentic and adequate requirements. Human evaluations further confirmed ReqBrain's effectiveness in generating requirements. Our findings suggest that generative Al, when fine-tuned, has the potential to improve requirements elicitation and specification, paving the way for future extensions into areas such as defect identification, test case generation, and agile user story creation.
