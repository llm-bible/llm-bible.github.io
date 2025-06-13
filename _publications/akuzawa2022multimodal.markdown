---
layout: publication
title: 'Multimodal Sequential Generative Models For Semi-supervised Language Instruction Following'
authors: Kei Akuzawa, Yusuke Iwasawa, Yutaka Matsuo
conference: "Arxiv"
year: 2022
bibkey: akuzawa2022multimodal
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2301.00676"}
tags: ['Transformer', 'Agentic', 'RAG', 'Model Architecture', 'Training Techniques', 'Attention Mechanism', 'Multimodal Models']
---
Agents that can follow language instructions are expected to be useful in a
variety of situations such as navigation. However, training neural
network-based agents requires numerous paired trajectories and languages. This
paper proposes using multimodal generative models for semi-supervised learning
in the instruction following tasks. The models learn a shared representation of
the paired data, and enable semi-supervised learning by reconstructing unpaired
data through the representation. Key challenges in applying the models to
sequence-to-sequence tasks including instruction following are learning a
shared representation of variable-length mulitimodal data and incorporating
attention mechanisms. To address the problems, this paper proposes a novel
network architecture to absorb the difference in the sequence lengths of the
multimodal data. In addition, to further improve the performance, this paper
shows how to incorporate the generative model-based approach with an existing
semi-supervised method called a speaker-follower model, and proposes a
regularization term that improves inference using unpaired trajectories.
Experiments on BabyAI and Room-to-Room (R2R) environments show that the
proposed method improves the performance of instruction following by leveraging
unpaired data, and improves the performance of the speaker-follower model by
2% to 4% in R2R.
