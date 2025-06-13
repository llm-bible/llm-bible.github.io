---
layout: publication
title: 'Safecomm: What About Safety Alignment In Fine-tuned Telecom Large Language Models?'
authors: Aladin Djuhera, Swanand Ravindra Kadhe, Farhan Ahmed, Syed Zawad, Holger Boche, Walid Saad
conference: "Arxiv"
year: 2025
bibkey: djuhera2025what
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2506.00062"}
tags: ['Responsible AI', 'Model Architecture', 'Training Techniques', 'Reinforcement Learning', 'Pretraining Methods', 'Fine-Tuning', 'Pre-Training', 'Applications', 'Attention Mechanism']
---
Fine-tuning large language models (LLMs) for telecom tasks and datasets is a common practice to adapt general-purpose models to the telecom domain. However, little attention has been paid to how this process may compromise model safety. Recent research has shown that even benign fine-tuning can degrade the safety alignment of LLMs, causing them to respond to harmful or unethical user queries. In this paper, we investigate this issue for telecom-tuned LLMs using three representative datasets featured by the GenAINet initiative. We show that safety degradation persists even for structured and seemingly harmless datasets such as 3GPP standards and tabular records, indicating that telecom-specific data is not immune to safety erosion during fine-tuning. We further extend our analysis to publicly available Telecom LLMs trained via continual pre-training, revealing that safety alignment is often severely lacking, primarily due to the omission of safety-focused instruction tuning. To address these issues in both fine-tuned and pre-trained models, we conduct extensive experiments and evaluate three safety realignment defenses (SafeInstruct, SafeLoRA, and SafeMERGE) using established red-teaming benchmarks. The results show that, across all settings, the proposed defenses can effectively restore safety after harmful degradation without compromising downstream task performance, leading to Safe teleCOMMunication (SafeCOMM) models. In a nutshell, our work serves as a diagnostic study and practical guide for safety realignment in telecom-tuned LLMs, and emphasizes the importance of safety-aware instruction and fine-tuning for real-world deployments of Telecom LLMs.
