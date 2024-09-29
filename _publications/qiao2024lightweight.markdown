---
layout: publication
title: LLM4SBR: A Lightweight And Effective Framework For Integrating Large Language Models In Session-based Recommendation
authors: Qiao Shutong, Gao Chen, Wen Junhao, Zhou Wei, Luo Qun, Chen Peixuan, Li Yong
conference: "Arxiv"
year: 2024
bibkey: qiao2024lightweight
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.13840"}
tags: ['Interpretability And Explainability', 'Pretraining Methods', 'RAG', 'Reinforcement Learning', 'Tools']
---
Traditional session-based recommendation (SBR) utilizes session behavior sequences from anonymous users for recommendation. Although this strategy is highly efficient it sacrifices the inherent semantic information of the items making it difficult for the model to understand the true intent of the session and resulting in a lack of interpretability in the recommended results. Recently large language models (LLMs) have flourished across various domains offering a glimpse of hope in addressing the aforementioned challenges. Inspired by the impact of LLMs research exploring the integration of LLMs with the Recommender system (RS) has surged like mushrooms after rain. However constrained by high time and space costs as well as the brief and anonymous nature of session data the first LLM recommendation framework suitable for industrial deployment has yet to emerge in the field of SBR. To address the aforementioned challenges we have proposed the LLM Integration Framework for SBR (LLM4SBR). Serving as a lightweight and plug-and-play framework LLM4SBR adopts a two-step strategy. Firstly we transform session data into a bimodal form of text and behavior. In the first step leveraging the inferential capabilities of LLMs we conduct inference on session text data from different perspectives and design the component for auxiliary enhancement. In the second step the SBR model is trained on behavior data aligning and averaging two modal session representations from different perspectives. Finally we fuse session representations from different perspectives and modalities as the ultimate session representation for recommendation. We conducted experiments on two real-world datasets and the results demonstrate that LLM4SBR significantly improves the performance of traditional SBR models and is highly lightweight and efficient making it suitable for industrial deployment.
