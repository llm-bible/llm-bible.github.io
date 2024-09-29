---
layout: publication
title: Pumer Pruning And Merging Tokens For Efficient Vision Language Models
authors: Cao Qingqing, Paranjape Bhargavi, Hajishirzi Hannaneh
conference: "Arxiv"
year: 2023
bibkey: cao2023pumer
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.17530"}
tags: ['Efficiency And Optimization', 'Merging', 'Model Architecture', 'Multimodal Models', 'Pretraining Methods', 'Pruning', 'Tools', 'Training Techniques', 'Transformer']
---
Large-scale vision language (VL) models use Transformers to perform cross-modal interactions between the input text and image. These cross-modal interactions are computationally expensive and memory-intensive due to the quadratic complexity of processing the input image and text. We present PuMer a token reduction framework that uses text-informed Pruning and modality-aware Merging strategies to progressively reduce the tokens of input image and text improving model inference speed and reducing memory footprint. PuMer learns to keep salient image tokens related to the input text and merges similar textual and visual tokens by adding lightweight token reducer modules at several cross-modal layers in the VL model. Training PuMer is mostly the same as finetuning the original VL model but faster. Our evaluation for two vision language models on four downstream VL tasks shows PuMer increases inference throughput by up to 2x and reduces memory footprint by over 5037; while incurring less than a 137; accuracy drop.
