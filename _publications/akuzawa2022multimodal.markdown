---
layout: publication
title: Multimodal Sequential Generative Models For Semi45;supervised Language Instruction Following
authors: Akuzawa Kei, Iwasawa Yusuke, Matsuo Yutaka
conference: "Arxiv"
year: 2022
bibkey: akuzawa2022multimodal
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2301.00676"}
tags: ['Agentic', 'Attention Mechanism', 'Model Architecture', 'Multimodal Models', 'RAG', 'Training Techniques', 'Transformer']
---
Agents that can follow language instructions are expected to be useful in a variety of situations such as navigation. However training neural network45;based agents requires numerous paired trajectories and languages. This paper proposes using multimodal generative models for semi45;supervised learning in the instruction following tasks. The models learn a shared representation of the paired data and enable semi45;supervised learning by reconstructing unpaired data through the representation. Key challenges in applying the models to sequence45;to45;sequence tasks including instruction following are learning a shared representation of variable45;length mulitimodal data and incorporating attention mechanisms. To address the problems this paper proposes a novel network architecture to absorb the difference in the sequence lengths of the multimodal data. In addition to further improve the performance this paper shows how to incorporate the generative model45;based approach with an existing semi45;supervised method called a speaker45;follower model and proposes a regularization term that improves inference using unpaired trajectories. Experiments on BabyAI and Room45;to45;Room (R2R) environments show that the proposed method improves the performance of instruction following by leveraging unpaired data and improves the performance of the speaker45;follower model by 237; to 437; in R2R.
