---
layout: publication
title: 'Improving Multi-modal Large Language Model Through Boosting Vision Capabilities'
authors: Yanpeng Sun, Huaxin Zhang, Qiang Chen, Xinyu Zhang, Nong Sang, Gang Zhang, Jingdong Wang, Zechao Li
conference: "Arxiv"
year: 2024
bibkey: sun2024improving
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.13733"}
  - {name: "Code", url: "https://arcana-project-page.github.io"}
tags: ['Multimodal Models', 'Reinforcement Learning', 'RAG', 'Fine-Tuning', 'Has Code']
---
We focus on improving the visual understanding capability for boosting the
vision-language models. We propose \textbf\{Arcana\}, a multiModal language
model, which introduces two crucial techniques. First, we present Multimodal
LoRA (MM-LoRA), a module designed to enhance the decoder. Unlike traditional
language-driven decoders, MM-LoRA consists of two parallel LoRAs -- one for
vision and one for language -- each with its own parameters. This disentangled
parameters design allows for more specialized learning in each modality and
better integration of multimodal information. Second, we introduce the Query
Ladder adapter (QLadder) to improve the visual encoder. QLadder employs a
learnable ``\textit\{ladder\}'' structure to deeply aggregates the intermediate
representations from the frozen pretrained visual encoder (e.g., CLIP image
encoder). This enables the model to learn new and informative visual features,
as well as remaining the powerful capabilities of the pretrained visual
encoder. These techniques collectively enhance Arcana's visual perception
power, enabling it to leverage improved visual information for more accurate
and contextually relevant outputs across various multimodal scenarios.
Extensive experiments and ablation studies demonstrate the effectiveness and
generalization capability of our Arcana. The code and re-annotated data are
available at \url\{https://arcana-project-page.github.io\}.
