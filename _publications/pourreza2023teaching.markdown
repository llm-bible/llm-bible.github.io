---
layout: publication
title: 'Painter: Teaching Auto-regressive Language Models To Draw Sketches'
authors: Reza Pourreza, Apratim Bhattacharyya, Sunny Panchal, Mingu Lee, Pulkit Madan, Roland Memisevic
conference: "Arxiv"
year: 2023
bibkey: pourreza2023teaching
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2308.08520'}
tags: ['Agentic', 'RAG', 'Training Techniques', 'Fine-Tuning', 'Prompting', 'Reinforcement Learning', 'Pretraining Methods']
---
Large language models (LLMs) have made tremendous progress in natural
language understanding and they have also been successfully adopted in other
domains such as computer vision, robotics, reinforcement learning, etc. In this
work, we apply LLMs to image generation tasks by directly generating the
virtual brush strokes to paint an image. We present Painter, an LLM that can
convert user prompts in text description format to sketches by generating the
corresponding brush strokes in an auto-regressive way. We construct Painter
based on off-the-shelf LLM that is pre-trained on a large text corpus, by
fine-tuning it on the new task while preserving language understanding
capabilities. We create a dataset of diverse multi-object sketches paired with
textual prompts that covers several object types and tasks. Painter can
generate sketches from text descriptions, remove objects from canvas, and
detect and classify objects in sketches. Although this is an unprecedented
pioneering work in using LLMs for auto-regressive image generation, the results
are very encouraging.
