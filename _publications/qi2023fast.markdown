---
layout: publication
title: Vidcom: Fast Video Comprehension Through Large Language Models With Multimodal Tools
authors: Qi Ji, Ji Kaixuan, Yu Jifan, Wang Duokang, Xu Bin, Hou Lei, Li Juanzi
conference: "Arxiv"
year: 2023
bibkey: qi2023fast
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.10586"}
tags: ['Agentic', 'Efficiency And Optimization', 'Multimodal Models', 'RAG', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
Building models that comprehends videos and responds specific user instructions is a practical and challenging topic as it requires mastery of both vision understanding and knowledge reasoning. Compared to language and image modalities training efficiency remains a serious problem as existing studies train models on massive sparse videos paired with brief descriptions. In this paper we introduce (textbfVidCoM) a fast adaptive framework that leverages Large Language Models (LLMs) to reason about videos using lightweight visual tools. Specifically we reveal that the key to responding to specific instructions is focusing on relevant video events and utilize two visual tools structured scene graph generation and descriptive image caption generation to gather and represent the event information. Thus a LLM enriched with world knowledge is adopted as the reasoning agent to achieve the responses by performing multiple reasoning steps on specific video events. To address the difficulty of LLMs identifying video events we further propose an Instruction-oriented Video Events Recognition (InsOVER) algorithm. This algorithm locates the corresponding video events based on an efficient Hungarian matching between decompositions of linguistic instructions and video events thereby enabling LLMs to interact effectively with extended videos. Extensive experiments on two typical video comprehension tasks show that the proposed tuning-free framework outperforms the pre-trained models including Flamingo-80B to achieve the state-of-the-art performance. Our source code and system will be publicly available.
