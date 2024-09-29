---
layout: publication
title: Medxchat A Unified Multimodal Large Language Model Framework Towards Cxrs Understanding And Generation
authors: Yang Ling, Wang Zhanyu, Chen Zhenghao, Liang Xinyu, Zhou Luping
conference: "Arxiv"
year: 2023
bibkey: yang2023medxchat
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.02233"}
tags: ['Applications', 'Fine Tuning', 'Merging', 'Model Architecture', 'Multimodal Models', 'RAG', 'Tools', 'Training Techniques']
---
Multimodal Large Language Models (MLLMs) have shown success in various general image processing tasks yet their application in medical imaging is nascent lacking tailored models. This study investigates the potential of MLLMs in improving the understanding and generation of Chest X-Rays (CXRs). We introduce MedXChat a unified framework facilitating seamless interactions between medical assistants and users for diverse CXR tasks including text report generation visual question-answering (VQA) and Text-to-CXR generation. Our MLLMs using natural language as the input breaks task boundaries maximally simplifying medical professional training by allowing diverse tasks within a single environment. For CXR understanding we leverage powerful off-the-shelf visual encoders (e.g. ViT) and LLMs (e.g. mPLUG-Owl) to convert medical imagery into language-like features and subsequently fine-tune our large pre-trained models for medical applications using a visual adapter network and a delta-tuning approach. For CXR generation we introduce an innovative synthesis approach that utilizes instruction-following capabilities within the Stable Diffusion (SD) architecture. This technique integrates smoothly with the existing model framework requiring no extra parameters thereby maintaining the SDs generative strength while also bestowing upon it the capacity to render fine-grained medical images with high fidelity. Through comprehensive experiments our model demonstrates exceptional cross-task adaptability displaying adeptness across all three defined tasks. Our MedXChat model and the instruction dataset utilized in this research will be made publicly available to encourage further exploration in the field.
