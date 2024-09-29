---
layout: publication
title: 'Brainchat: Decoding Semantic Information From Fmri Using Vision-language Pretrained Models'
authors: Huang Wanaiu
conference: "Arxiv"
year: 2024
bibkey: huang2024decoding
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.07584"}
tags: ['Applications', 'Attention Mechanism', 'Model Architecture', 'Multimodal Models', 'RAG', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
Semantic information is vital for human interaction and decoding it from brain activity enables non-invasive clinical augmentative and alternative communication. While there has been significant progress in reconstructing visual images few studies have focused on the language aspect. To address this gap leveraging the powerful capabilities of the decoder-based vision-language pretrained model CoCa this paper proposes BrainChat a simple yet effective generative framework aimed at rapidly accomplishing semantic information decoding tasks from brain activity including fMRI question answering and fMRI captioning. BrainChat employs the self-supervised approach of Masked Brain Modeling to encode sparse fMRI data obtaining a more compact embedding representation in the latent space. Subsequently BrainChat bridges the gap between modalities by applying contrastive loss resulting in aligned representations of fMRI image and text embeddings. Furthermore the fMRI embeddings are mapped to the generative Brain Decoder via cross-attention layers where they guide the generation of textual content about fMRI in a regressive manner by minimizing caption loss. Empirically BrainChat exceeds the performance of existing state-of-the-art methods in the fMRI captioning task and for the first time implements fMRI question answering. Additionally BrainChat is highly flexible and can achieve high performance without image data making it better suited for real-world scenarios with limited data.
