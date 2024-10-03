---
layout: publication
title: 'LIME-M: Less Is More For Evaluation Of Mllms'
authors: Zhu Kang, Zang Qianbo, Jia Shian, Wu Siwei, Fang Feiteng, Li Yizhi, Guo Shuyue, Zheng Tianyu, Li Bo, Wu Haoning, Qu Xingwei, Yang Jian, Liu Zachary, Yue Xiang, Liu J. H., Lin Chenghua, Yang Min, Ni Shiwen, Huang Wenhao, Zhang Ge
conference: "Arxiv"
year: 2024
bibkey: zhu2024lime
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.06851"}
  - {name: "Code", url: "https://github.com/kangreen0210/LIME-M"}
tags: ['Applications', 'Has Code', 'Multimodal Models', 'Reinforcement Learning']
---
With the remarkable success achieved by Multimodal Large Language Models (MLLMs), numerous benchmarks have been designed to assess MLLMs' ability to guide their development in image perception tasks (e.g., image captioning and visual question answering). However, the existence of numerous benchmarks results in a substantial computational burden when evaluating model performance across all of them. Moreover, these benchmarks contain many overly simple problems or challenging samples, which do not effectively differentiate the capabilities among various MLLMs. To address these challenges, we propose a pipeline to process the existing benchmarks, which consists of two modules: (1) Semi-Automated Screening Process and (2) Eliminating Answer Leakage. The Semi-Automated Screening Process filters out samples that cannot distinguish the model's capabilities by synthesizing various MLLMs and manually evaluating them. The Eliminate Answer Leakage module filters samples whose answers can be inferred without images. Finally, we curate the LIME-M: Less Is More for Evaluation of Multimodal LLMs, a lightweight Multimodal benchmark that can more effectively evaluate the performance of different models. Our experiments demonstrate that: LIME-M can better distinguish the performance of different MLLMs with fewer samples (24&#37; of the original) and reduced time (23&#37; of the original); LIME-M eliminates answer leakage, focusing mainly on the information within images; The current automatic metric (i.e., CIDEr) is insufficient for evaluating MLLMs' capabilities in captioning. Moreover, removing the caption task score when calculating the overall score provides a more accurate reflection of model performance differences. All our codes and data are released at https://github.com/kangreen0210/LIME-M.
