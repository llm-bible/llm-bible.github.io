---
layout: publication
title: 'Vitextvqa: A Large-scale Visual Question Answering Dataset For Evaluating Vietnamese Text Comprehension In Images'
authors: Quan Van Nguyen, Dan Quang Tran, Huy Quang Pham, Thang Kien-bao Nguyen, Nghia Hieu Nguyen, Kiet Van Nguyen, Ngan Luu-thuy Nguyen
conference: "Arxiv"
year: 2024
bibkey: vannguyen2024large
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2404.10652'}
  - {name: "Code", url: 'https://github.com/minhquan6203/ViTextVQA-Dataset)'}
tags: ['Has Code', 'Transformer', 'Model Architecture', 'Applications', 'Merging', 'Multimodal Models', 'Reinforcement Learning', 'Pretraining Methods']
---
Visual Question Answerinng (VQA) is a complicated task that requires the capability of simultaneously processing natural language and images. This task was initially researched with a focus on developing methods to help machines understand objects and scene contexts in images. However, some scene text that carries explicit information about the full content of the image is not mentioned. Along with the continuous development of the AI era, there have been many studies on the reading comprehension ability of VQA models in the world. Therefore, we introduce the first large-scale dataset in Vietnamese specializing in the ability to understand scene text, we call it ViTextVQA (\textbf\{Vi\}etnamese \textbf\{Text\}-based \textbf\{V\}isual \textbf\{Q\}uestion \textbf\{A\}nswering dataset) which contains \textbf\{over 16,000\} images and \textbf\{over 50,000\} questions with answers. To tackle this task efficiently, we propose ViTextBLIP-2, an novel multimodal feature fusion Method, which optimizes Vietnamese OCR-based VQA by integrating a frozen Vision Transformer, SwinTextSpotter OCR, and ViT5 LLM with a trainable Q-Former for multimodal feature fusion. Through experiments with various state-of-the-art models, we uncover the significance of the order in which tokens in OCR text are processed and selected to formulate answers. This finding helped us significantly improve the performance of the baseline models on the ViTextVQA dataset. Our dataset is available (https://github.com/minhquan6203/ViTextVQA-Dataset) for research purposes.
