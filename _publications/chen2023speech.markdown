---
layout: publication
title: SALM Speech45;augmented Language Model With In45;context Learning For Speech Recognition And Translation
authors: Chen Zhehuai, Huang He, Andrusenko Andrei, Hrinchuk Oleksii, Puvvada Krishna C., Li Jason, Ghosh Subhankar, Balam Jagadeesh, Ginsburg Boris
conference: "Arxiv"
year: 2023
bibkey: chen2023speech
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.09424"}
tags: ['Fine Tuning', 'Pretraining Methods', 'Training Techniques']
---
We present a novel Speech Augmented Language Model (SALM) with 123;em multitask125; and 123;em in45;context125; learning capabilities. SALM comprises a frozen text LLM a audio encoder a modality adapter module and LoRA layers to accommodate speech input and associated task instructions. The unified SALM not only achieves performance on par with task45;specific Conformer baselines for Automatic Speech Recognition (ASR) and Speech Translation (AST) but also exhibits zero45;shot in45;context learning capabilities demonstrated through keyword45;boosting task for ASR and AST. Moreover 123;em speech supervised in45;context training125; is proposed to bridge the gap between LLM training and downstream speech tasks which further boosts the in45;context learning ability of speech45;to45;text models. Proposed model is open45;sourced via NeMo toolkit.
