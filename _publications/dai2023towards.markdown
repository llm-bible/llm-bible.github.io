---
layout: publication
title: Instructblip Towards General45;purpose Vision45;language Models With Instruction Tuning
authors: Wenliang Dai, Junnan Li, Dongxu Li, Anthony Meng Huat Tiong, Junqi Zhao, Weisheng Wang, Boyang Li, Pascale Fung, Steven Hoi
conference: "Arxiv"
year: 2023
bibkey: dai2023towards
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/http://arxiv.org/abs/2305.06500v2"}
  - {name: "Code", url: "https://github.com/salesforce/LAVIS/tree/main/projects/instructblip"}
tags: ['Has Code', 'Model Architecture', 'Multimodal Models', 'Pretraining Methods', 'Survey Paper', 'Training Techniques', 'Transformer']
---
Large45;scale pre45;training and instruction tuning have been successful at creating general45;purpose language models with broad competence. However building general45;purpose vision45;language models is challenging due to the rich input distributions and task diversity resulting from the additional visual input. Although vision45;language pretraining has been widely studied vision45;language instruction tuning remains under45;explored. In this paper we conduct a systematic and comprehensive study on vision45;language instruction tuning based on the pretrained BLIP45;2 models. We gather 26 publicly available datasets covering a wide variety of tasks and capabilities and transform them into instruction tuning format. Additionally we introduce an instruction45;aware Query Transformer which extracts informative features tailored to the given instruction. Trained on 13 held45;in datasets InstructBLIP attains state45;of45;the45;art zero45;shot performance across all 13 held45;out datasets substantially outperforming BLIP45;2 and larger Flamingo models. Our models also lead to state45;of45;the45;art performance when finetuned on individual downstream tasks (e.g. 90.737; accuracy on ScienceQA questions with image contexts). Furthermore we qualitatively demonstrate the advantages of InstructBLIP over concurrent multimodal models. All InstructBLIP models are open45;sourced at https://github.com/salesforce/LAVIS/tree/main/projects/instructblip.
