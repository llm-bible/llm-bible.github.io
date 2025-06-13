---
layout: publication
title: 'Compositional Text-to-image Generation With Dense Blob Representations'
authors: Weili Nie, Sifei Liu, Morteza Mardani, Chao Liu, Benjamin Eckart, Arash Vahdat
conference: "Arxiv"
year: 2024
bibkey: nie2024compositional
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2405.08246'}
tags: ['Attention Mechanism', 'RAG', 'Model Architecture', 'Merging', 'Prompting', 'Reinforcement Learning', 'In-Context Learning']
---
Existing text-to-image models struggle to follow complex text prompts,
raising the need for extra grounding inputs for better controllability. In this
work, we propose to decompose a scene into visual primitives - denoted as dense
blob representations - that contain fine-grained details of the scene while
being modular, human-interpretable, and easy-to-construct. Based on blob
representations, we develop a blob-grounded text-to-image diffusion model,
termed BlobGEN, for compositional generation. Particularly, we introduce a new
masked cross-attention module to disentangle the fusion between blob
representations and visual features. To leverage the compositionality of large
language models (LLMs), we introduce a new in-context learning approach to
generate blob representations from text prompts. Our extensive experiments show
that BlobGEN achieves superior zero-shot generation quality and better
layout-guided controllability on MS-COCO. When augmented by LLMs, our method
exhibits superior numerical and spatial correctness on compositional image
generation benchmarks. Project page: https://blobgen-2d.github.io.
