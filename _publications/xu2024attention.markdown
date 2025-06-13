---
layout: publication
title: 'Attention-driven GUI Grounding: Leveraging Pretrained Multimodal Large Language Models Without Fine-tuning'
authors: Hai-ming Xu, Qi Chen, Lei Wang, Lingqiao Liu
conference: "Arxiv"
year: 2024
bibkey: xu2024attention
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.10840"}
tags: ['Fine-Tuning', 'RAG', 'Model Architecture', 'Training Techniques', 'Attention Mechanism', 'Pretraining Methods', 'Multimodal Models', 'Prompting']
---
Recent advancements in Multimodal Large Language Models (MLLMs) have
generated significant interest in their ability to autonomously interact with
and interpret Graphical User Interfaces (GUIs). A major challenge in these
systems is grounding-accurately identifying critical GUI components such as
text or icons based on a GUI image and a corresponding text query.
Traditionally, this task has relied on fine-tuning MLLMs with specialized
training data to predict component locations directly. However, in this paper,
we propose a novel Tuning-free Attention-driven Grounding (TAG) method that
leverages the inherent attention patterns in pretrained MLLMs to accomplish
this task without the need for additional fine-tuning. Our method involves
identifying and aggregating attention maps from specific tokens within a
carefully constructed query prompt. Applied to MiniCPM-Llama3-V 2.5, a
state-of-the-art MLLM, our tuning-free approach achieves performance comparable
to tuning-based methods, with notable success in text localization.
Additionally, we demonstrate that our attention map-based grounding technique
significantly outperforms direct localization predictions from MiniCPM-Llama3-V
2.5, highlighting the potential of using attention maps from pretrained MLLMs
and paving the way for future innovations in this domain.
