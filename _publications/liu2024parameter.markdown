---
layout: publication
title: "Pefomed: Parameter Efficient Fine-tuning Of Multimodal Large Language Models For Medical Imaging"
authors: Liu Gang, He Jinlong, Li Pengfei, He Genrong, Chen Zhaolin, Zhong Shenjun
conference: "Arxiv"
year: 2024
bibkey: liu2024parameter
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.02797"}
  - {name: "Code", url: "https://github.com/jinlHe/PeFoMed"}
tags: ['Applications', 'Fine Tuning', 'GPT', 'Has Code', 'Model Architecture', 'Multimodal Models', 'Pretraining Methods', 'RAG', 'Tools', 'Training Techniques']
---
Multimodal large language models (MLLMs) represent an evolutionary expansion in the capabilities of traditional large language models enabling them to tackle challenges that surpass the scope of purely text-based applications. It leverages the knowledge previously encoded within these language models thereby enhancing their applicability and functionality in the reign of multimodal contexts. Recent works investigate the adaptation of MLLMs as a universal solution to address medical multi-modal problems as a generative task. In this paper we propose a parameter efficient framework for fine-tuning MLLMs specifically validated on medical visual question answering (Med-VQA) and medical report generation (MRG) tasks using public benchmark datasets. We also introduce an evaluation metric using the 5-point Likert scale and its weighted average value to measure the quality of the generated reports for MRG tasks where the scale ratings are labelled by both humans manually and the GPT-4 model. We further assess the consistency of performance metrics across traditional measures GPT-4 and human ratings for both VQA and MRG tasks. The results indicate that semantic similarity assessments using GPT-4 align closely with human annotators and provide greater stability yet they reveal a discrepancy when compared to conventional lexical similarity measurements. This questions the reliability of lexical similarity metrics for evaluating the performance of generative models in Med-VQA and report generation tasks. Besides our fine-tuned model significantly outperforms GPT-4v. This indicates that without additional fine-tuning multi-modal models like GPT-4v do not perform effectively on medical imaging tasks. The code will be available here https://github.com/jinlHe/PeFoMed."
