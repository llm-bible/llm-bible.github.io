---
layout: publication
title: 'SALM: Speech-augmented Language Model With In-context Learning For Speech Recognition And Translation'
authors: Chen Zhehuai, Huang He, Andrusenko Andrei, Hrinchuk Oleksii, Puvvada Krishna C., Li Jason, Ghosh Subhankar, Balam Jagadeesh, Ginsburg Boris
conference: "Arxiv"
year: 2023
bibkey: chen2023speech
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.09424"}
tags: ['Fine Tuning', 'In Context Learning', 'Prompting', 'Training Techniques']
---
"We present a novel Speech Augmented Language Model (SALM) with \{\em multitask\} and \{\em in-context\} learning capabilities. SALM comprises a frozen text LLM, a audio encoder, a modality adapter module, and LoRA layers to accommodate speech input and associated task instructions. The unified SALM not only achieves performance on par with task-specific Conformer baselines for Automatic Speech Recognition (ASR) and Speech Translation (AST), but also exhibits zero-shot in-context learning capabilities, demonstrated through keyword-boosting task for ASR and AST. Moreover, \{\em speech supervised in-context training\} is proposed to bridge the gap between LLM training and downstream speech tasks, which further boosts the in-context learning ability of speech-to-text models. Proposed model is open-sourced via NeMo toolkit."
