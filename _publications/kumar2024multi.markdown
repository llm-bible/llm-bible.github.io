---
layout: publication
title: Multi-modal Generation Via Cross-modal In-context Learning
authors: Kumar Amandeep, Naseer Muzammal, Narayan Sanath, Anwer Rao Muhammad, Khan Salman, Cholakkal Hisham
conference: "Arxiv"
year: 2024
bibkey: kumar2024multi
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.18304"}
  - {name: "Code", url: "https://github.com/VIROBO-15/MGCC"}
tags: ['Has Code', 'In Context Learning', 'Merging', 'Multimodal Models', 'Prompting', 'RAG', 'Reinforcement Learning']
---
In this work we study the problem of generating novel images from complex multimodal prompt sequences. While existing methods achieve promising results for text-to-image generation they often struggle to capture fine-grained details from lengthy prompts and maintain contextual coherence within prompt sequences. Moreover they often result in misaligned image generation for prompt sequences featuring multiple objects. To address this we propose a Multi-modal Generation via Cross-Modal In-Context Learning (MGCC) method that generates novel images from complex multimodal prompt sequences by leveraging the combined capabilities of large language models (LLMs) and diffusion models. Our MGCC comprises a novel Cross-Modal Refinement module to explicitly learn cross-modal dependencies between the text and image in the LLM embedding space and a contextual object grounding module to generate object bounding boxes specifically targeting scenes with multiple objects. Our MGCC demonstrates a diverse range of multimodal capabilities like novel image generation the facilitation of multimodal dialogue and generation of texts. Experimental evaluations on two benchmark datasets demonstrate the effectiveness of our method. On Visual Story Generation (VIST) dataset with multimodal inputs our MGCC achieves a CLIP Similarity score of 0.652 compared to SOTA GILL 0.641. Similarly on Visual Dialogue Context (VisDial) having lengthy dialogue sequences our MGCC achieves an impressive CLIP score of 0.660 largely outperforming existing SOTA method scoring 0.645. Code https://github.com/VIROBO-15/MGCC"
