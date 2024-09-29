---
layout: publication
title: Instruction-Guided Scene Text Recognition
authors: Du Yongkun, Chen Zhineng, Su Yuchen, Jia Caiyan, Jiang Yu-gang
conference: "Arxiv"
year: 2024
bibkey: du2024instruction
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.17851"}
  - {name: "Code", url: "https://github.com/Topdu/OpenOCRthis"}
tags: ['Has Code', 'Merging', 'Multimodal Models', 'Reinforcement Learning', 'Training Techniques']
---
Multi-modal models show appealing performance in visual recognition tasks recently as free-form text-guided training evokes the ability to understand fine-grained visual content. However current models are either inefficient or cannot be trivially upgraded to scene text recognition (STR) due to the composition difference between natural and text images. We propose a novel instruction-guided scene text recognition (IGTR) paradigm that formulates STR as an instruction learning problem and understands text images by predicting character attributes e.g. character frequency position etc. IGTR first devises left langle conditionquestionanswerright rangle instruction triplets providing rich and diverse descriptions of character attributes. To effectively learn these attributes through question-answering IGTR develops lightweight instruction encoder cross-modal feature fusion module and multi-task answer head which guides nuanced text image understanding. Furthermore IGTR realizes different recognition pipelines simply by using different instructions enabling a character-understanding-based text reasoning paradigm that considerably differs from current methods. Experiments on English and Chinese benchmarks show that IGTR outperforms existing models by significant margins while maintaining a small model size and efficient inference speed. Moreover by adjusting the sampling of instructions IGTR offers an elegant way to tackle the recognition of both rarely appearing and morphologically similar characters which were previous challenges. Code at href https://github.com/Topdu/OpenOCRthis http URL.
