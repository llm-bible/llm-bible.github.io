---
layout: publication
title: Unifying Vision45;and45;language Tasks Via Text Generation
authors: Cho Jaemin, Lei Jie, Tan Hao, Bansal Mohit
conference: "Arxiv"
year: 2021
bibkey: cho2021unifying
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2102.02779"}
  - {name: "Code", url: "https://github.com/j&#45;min/VL&#45;T5"}
tags: ['Applications', 'Has Code', 'Language Modeling', 'Model Architecture', 'Multimodal Models', 'Tools']
---
Existing methods for vision45;and45;language learning typically require designing task45;specific architectures and objectives for each task. For example a multi45;label answer classifier for visual question answering a region scorer for referring expression comprehension and a language decoder for image captioning etc. To alleviate these hassles in this work we propose a unified framework that learns different tasks in a single architecture with the same language modeling objective i.e. multimodal conditional text generation where our models learn to generate labels in text based on the visual and textual inputs. On 7 popular vision45;and45;language benchmarks including visual question answering referring expression comprehension visual commonsense reasoning most of which have been previously modeled as discriminative tasks our generative approach (with a single unified architecture) reaches comparable performance to recent task45;specific state45;of45;the45;art vision45;and45;language models. Moreover our generative approach shows better generalization ability on questions that have rare answers. Also we show that our framework allows multi45;task learning in a single architecture with a single set of parameters achieving similar performance to separately optimized single45;task models. Our code is publicly available at https://github.com/j&#45;min/VL&#45;T5
