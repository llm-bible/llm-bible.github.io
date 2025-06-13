---
layout: publication
title: 'Enhanced Multimodal RAG-LLM For Accurate Visual Question Answering'
authors: Junxiao Xue, Quan Deng, Fei Yu, Yanhao Wang, Jun Wang, Yuehua Li
conference: "Arxiv"
year: 2024
bibkey: xue2024enhanced
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2412.20927'}
tags: ['RAG', 'Model Architecture', 'Tools', 'Applications', 'GPT', 'Multimodal Models', 'Reinforcement Learning']
---
Multimodal large language models (MLLMs), such as GPT-4o, Gemini, LLaVA, and
Flamingo, have made significant progress in integrating visual and textual
modalities, excelling in tasks like visual question answering (VQA), image
captioning, and content retrieval. They can generate coherent and contextually
relevant descriptions of images. However, they still face challenges in
accurately identifying and counting objects and determining their spatial
locations, particularly in complex scenes with overlapping or small objects. To
address these limitations, we propose a novel framework based on multimodal
retrieval-augmented generation (RAG), which introduces structured scene graphs
to enhance object recognition, relationship identification, and spatial
understanding within images. Our framework improves the MLLM's capacity to
handle tasks requiring precise visual descriptions, especially in scenarios
with challenging perspectives, such as aerial views or scenes with dense object
arrangements. Finally, we conduct extensive experiments on the VG-150 dataset
that focuses on first-person visual understanding and the AUG dataset that
involves aerial imagery. The results show that our approach consistently
outperforms existing MLLMs in VQA tasks, which stands out in recognizing,
localizing, and quantifying objects in different spatial contexts and provides
more accurate visual descriptions.
