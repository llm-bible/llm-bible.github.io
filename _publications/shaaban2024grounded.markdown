---
layout: publication
title: Medpromptx&#58; Grounded Multimodal Prompting For Chest X-ray Diagnosis
authors: Shaaban Mai A., Khan Adnan, Yaqub Mohammad
conference: "Arxiv"
year: 2024
bibkey: shaaban2024grounded
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.15585"}
  - {name: "Code", url: "https://github.com/BioMedIA-MBZUAI/MedPromptX"}
tags: ['Applications', 'Attention Mechanism', 'Few Shot', 'Has Code', 'In Context Learning', 'Model Architecture', 'Multimodal Models', 'Prompting', 'Reinforcement Learning', 'Training Techniques']
---
Chest X-ray images are commonly used for predicting acute and chronic cardiopulmonary conditions but efforts to integrate them with structured clinical data face challenges due to incomplete electronic health records (EHR). This paper introduces MedPromptX the first model to integrate multimodal large language models (MLLMs) few-shot prompting (FP) and visual grounding (VG) to combine imagery with EHR data for chest X-ray diagnosis. A pre-trained MLLM is utilized to complement the missing EHR information providing a comprehensive understanding of patients medical history. Additionally FP reduces the necessity for extensive training of MLLMs while effectively tackling the issue of hallucination. Nevertheless the process of determining the optimal number of few-shot examples and selecting high-quality candidates can be burdensome yet it profoundly influences model performance. Hence we propose a new technique that dynamically refines few-shot data for real-time adjustment to new patient scenarios. Moreover VG aids in focusing the models attention on relevant regions of interest in X-ray images enhancing the identification of abnormalities. We release MedPromptX-VQA a new in-context visual question answering dataset encompassing interleaved image and EHR data derived from MIMIC-IV and MIMIC-CXR databases. Results demonstrate the SOTA performance of MedPromptX achieving an 1137; improvement in F1-score compared to the baselines. Code and data are available at https://github.com/BioMedIA-MBZUAI/MedPromptX"
