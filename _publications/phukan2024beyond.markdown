---
layout: publication
title: 'Beyond Logit Lens: Contextual Embeddings For Robust Hallucination Detection & Grounding In Vlms'
authors: Anirudh Phukan, Divyansh, Harshit Kumar Morj, Vaishnavi, Apoorv Saxena, Koustava Goswami
conference: "Arxiv"
year: 2024
bibkey: phukan2024beyond
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.19187"}
tags: ['Tools', 'Applications', 'RAG', 'Training Techniques', 'Multimodal Models']
---
The rapid development of Large Multimodal Models (LMMs) has significantly
advanced multimodal understanding by harnessing the language abilities of Large
Language Models (LLMs) and integrating modality-specific encoders. However,
LMMs are plagued by hallucinations that limit their reliability and adoption.
While traditional methods to detect and mitigate these hallucinations often
involve costly training or rely heavily on external models, recent approaches
utilizing internal model features present a promising alternative. In this
paper, we critically assess the limitations of the state-of-the-art
training-free technique, the logit lens, in handling generalized visual
hallucinations. We introduce ContextualLens, a refined method that leverages
contextual token embeddings from middle layers of LMMs. This approach
significantly improves hallucination detection and grounding across diverse
categories, including actions and OCR, while also excelling in tasks requiring
contextual understanding, such as spatial relations and attribute comparison.
Our novel grounding technique yields highly precise bounding boxes,
facilitating a transition from Zero-Shot Object Segmentation to Grounded Visual
Question Answering. Our contributions pave the way for more reliable and
interpretable multimodal models.
