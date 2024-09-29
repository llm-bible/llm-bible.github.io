---
layout: publication
title: MMIDR Teaching Large Language Model To Interpret Multimodal Misinformation Via Knowledge Distillation
authors: Wang Longzheng, Xu Xiaohan, Zhang Lei, Lu Jiarui, Xu Yongxiu, Xu Hongbo, Tang Minghao, Zhang Chuang
conference: "Arxiv"
year: 2024
bibkey: wang2024mmidr
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.14171"}
tags: ['Attention Mechanism', 'Distillation', 'Efficiency And Optimization', 'Interpretability And Explainability', 'Model Architecture', 'Multimodal Models', 'Prompting', 'Reinforcement Learning', 'Tools']
---
Automatic detection of multimodal misinformation has gained a widespread attention recently. However the potential of powerful Large Language Models (LLMs) for multimodal misinformation detection remains underexplored. Besides how to teach LLMs to interpret multimodal misinformation in cost-effective and accessible way is still an open question. To address that we propose MMIDR a framework designed to teach LLMs in providing fluent and high-quality textual explanations for their decision-making process of multimodal misinformation. To convert multimodal misinformation into an appropriate instruction-following format we present a data augmentation perspective and pipeline. This pipeline consists of a visual information processing module and an evidence retrieval module. Subsequently we prompt the proprietary LLMs with processed contents to extract rationales for interpreting the authenticity of multimodal misinformation. Furthermore we design an efficient knowledge distillation approach to distill the capability of proprietary LLMs in explaining multimodal misinformation into open-source LLMs. To explore several research questions regarding the performance of LLMs in multimodal misinformation detection tasks we construct an instruction-following multimodal misinformation dataset and conduct comprehensive experiments. The experimental findings reveal that our MMIDR exhibits sufficient detection performance and possesses the capacity to provide compelling rationales to support its assessments.
