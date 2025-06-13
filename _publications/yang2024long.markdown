---
layout: publication
title: 'Logu: Long-form Generation With Uncertainty Expressions'
authors: Ruihan Yang, Caiqi Zhang, Zhisong Zhang, Xinting Huang, Sen Yang, Nigel Collier, Dong Yu, Deqing Yang
conference: "Arxiv"
year: 2024
bibkey: yang2024long
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.14309"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Tools', 'Reinforcement Learning', 'Pretraining Methods', 'Fine-Tuning', 'Applications']
---
While Large Language Models (LLMs) demonstrate impressive capabilities, they still struggle with generating factually incorrect content (i.e., hallucinations). A promising approach to mitigate this issue is enabling models to express uncertainty when unsure. Previous research on uncertainty modeling has primarily focused on short-form QA, but realworld applications often require much longer responses. In this work, we introduce the task of Long-form Generation with Uncertainty(LoGU). We identify two key challenges: Uncertainty Suppression, where models hesitate to express uncertainty, and Uncertainty Misalignment, where models convey uncertainty inaccurately. To tackle these challenges, we propose a refinement-based data collection framework and a two-stage training pipeline. Our framework adopts a divide-and-conquer strategy, refining uncertainty based on atomic claims. The collected data are then used in training through supervised fine-tuning (SFT) and direct preference optimization (DPO) to enhance uncertainty expression. Extensive experiments on three long-form instruction following datasets show that our method significantly improves accuracy, reduces hallucinations, and maintains the comprehensiveness of responses.
