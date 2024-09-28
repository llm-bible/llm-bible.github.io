---
layout: publication
title: LLMs as Visual Explainers Advancing Image Classification with Evolving Visual Descriptions
authors: Han Songhao, Zhuo Le, Liao Yue, Liu Si
conference: "Arxiv"
year: 2023
bibkey: han2023llms
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.11904"}
tags: ['ARXIV', 'Agentic', 'Efficiency And Optimization', 'Fine Tuning', 'LLM', 'RAG', 'Tools']
---
Vision-language models (VLMs) offer a promising paradigm for image classification by comparing the similarity between images and class embeddings. A critical challenge lies in crafting precise textual representations for class names. While previous studies have leveraged recent advancements in large language models (LLMs) to enhance these descriptors their outputs often suffer from ambiguity and inaccuracy. We attribute this to two primary factors 1) the reliance on single-turn textual interactions with LLMs leading to a mismatch between generated text and visual concepts for VLMs; 2) the oversight of the inter-class relationships resulting in descriptors that fail to differentiate similar classes effectively. In this paper we propose a novel framework that integrates LLMs and VLMs to find the optimal class descriptors. Our training-free approach develops an LLM-based agent with an evolutionary optimization strategy to iteratively refine class descriptors. We demonstrate our optimized descriptors are of high quality which effectively improves classification accuracy on a wide range of benchmarks. Additionally these descriptors offer explainable and robust features boosting performance across various backbone models and complementing fine-tuning-based methods.
