---
layout: publication
title: 'Test-time Contrastive Concepts For Open-world Semantic Segmentation'
authors: Monika Wysoczańska, Antonin Vobecky, Amaia Cardiel, Tomasz Trzciński, Renaud Marlet, Andrei Bursuc, Oriane Siméoni
conference: "Arxiv"
year: 2024
bibkey: wysoczańska2024test
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.05061"}
tags: ['Multimodal Models', 'Training Techniques', 'Reinforcement Learning', 'RAG', 'Prompting']
---
Recent CLIP-like Vision-Language Models (VLMs), pre-trained on large amounts
of image-text pairs to align both modalities with a simple contrastive
objective, have paved the way to open-vocabulary semantic segmentation. Given
an arbitrary set of textual queries, image pixels are assigned the closest
query in feature space. However, this works well when a user exhaustively lists
all possible visual concepts in an image, which contrast against each other for
the assignment. This corresponds to the current evaluation setup in the
literature which relies on having access to a list of in-domain relevant
concepts, typically classes of a benchmark dataset. Here, we consider the more
challenging (and realistic) scenario of segmenting a single concept, given a
textual prompt and nothing else. To achieve good results, besides contrasting
with the generic \\(\textit\{background\}\\) text, we propose two different
approaches to automatically generate, at test time, textual contrastive
concepts that are query-specific. We do so by leveraging the distribution of
text in the VLM's training set or crafted LLM prompts. We also propose a metric
designed to evaluate this scenario and show the relevance of our approach to
commonly used datasets.
