---
layout: publication
title: 'Look & Mark: Leveraging Radiologist Eye Fixations And Bounding Boxes In Multimodal Large Language Models For Chest X-ray Report Generation'
authors: Yunsoo Kim, Jinge Wu, Su-hwan Kim, Pardeep Vasudev, Jiashu Shen, Honghan Wu
conference: "Arxiv"
year: 2025
bibkey: kim2025look
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.22222"}
tags: ['Multimodal Models', 'Training Techniques', 'Tools', 'Reinforcement Learning', 'RAG', 'Pretraining Methods', 'Fine-Tuning', 'Prompting', 'Applications', 'In-Context Learning']
---
Recent advancements in multimodal Large Language Models (LLMs) have significantly enhanced the automation of medical image analysis, particularly in generating radiology reports from chest X-rays (CXR). However, these models still suffer from hallucinations and clinically significant errors, limiting their reliability in real-world applications. In this study, we propose Look & Mark (L&M), a novel grounding fixation strategy that integrates radiologist eye fixations (Look) and bounding box annotations (Mark) into the LLM prompting framework. Unlike conventional fine-tuning, L&M leverages in-context learning to achieve substantial performance gains without retraining. When evaluated across multiple domain-specific and general-purpose models, L&M demonstrates significant gains, including a 1.2% improvement in overall metrics (A.AVG) for CXR-LLaVA compared to baseline prompting and a remarkable 9.2% boost for LLaVA-Med. General-purpose models also benefit from L&M combined with in-context learning, with LLaVA-OV achieving an 87.3% clinical average performance (C.AVG)-the highest among all models, even surpassing those explicitly trained for CXR report generation. Expert evaluations further confirm that L&M reduces clinically significant errors (by 0.43 average errors per report), such as false predictions and omissions, enhancing both accuracy and reliability. These findings highlight L&M's potential as a scalable and efficient solution for AI-assisted radiology, paving the way for improved diagnostic workflows in low-resource clinical settings.
