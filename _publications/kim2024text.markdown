---
layout: publication
title: 'Text Embedding Is Not All You Need: Attention Control For Text-to-image Semantic Alignment With Text Self-attention Maps'
authors: Jeeyung Kim, Erfan Esmaeili, Qiang Qiu
conference: "Arxiv"
year: 2024
bibkey: kim2024text
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2411.15236'}
tags: ['Attention Mechanism', 'Transformer', 'RAG', 'Efficiency and Optimization', 'Model Architecture', 'Merging', 'Prompting', 'Multimodal Models', 'Reinforcement Learning']
---
In text-to-image diffusion models, the cross-attention map of each text token
indicates the specific image regions attended. Comparing these maps of
syntactically related tokens provides insights into how well the generated
image reflects the text prompt. For example, in the prompt, "a black car and a
white clock", the cross-attention maps for "black" and "car" should focus on
overlapping regions to depict a black car, while "car" and "clock" should not.
Incorrect overlapping in the maps generally produces generation flaws such as
missing objects and incorrect attribute binding. Our study makes the key
observations investigating this issue in the existing text-to-image models:(1)
the similarity in text embeddings between different tokens -- used as
conditioning inputs -- can cause their cross-attention maps to focus on the
same image regions; and (2) text embeddings often fail to faithfully capture
syntactic relations already within text attention maps. As a result, such
syntactic relationships can be overlooked in cross-attention module, leading to
inaccurate image generation. To address this, we propose a method that directly
transfers syntactic relations from the text attention maps to the
cross-attention module via a test-time optimization. Our approach leverages
this inherent yet unexploited information within text attention maps to enhance
image-text semantic alignment across diverse prompts, without relying on
external guidance.
