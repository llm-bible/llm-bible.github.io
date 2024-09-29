---
layout: publication
title: Pumer Pruning And Merging Tokens For Efficient Vision Language Models
authors: Cao Qingqing, Paranjape Bhargavi, Hajishirzi Hannaneh
conference: "Arxiv"
year: 2023
bibkey: cao2023pruning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.17530"}
tags: ['Efficiency And Optimization', 'Merging', 'Model Architecture', 'Pretraining Methods', 'Pruning', 'Tools', 'Training Techniques', 'Transformer']
---
Large45;scale vision language (VL) models use Transformers to perform cross45;modal interactions between the input text and image. These cross45;modal interactions are computationally expensive and memory45;intensive due to the quadratic complexity of processing the input image and text. We present PuMer a token reduction framework that uses text45;informed Pruning and modality45;aware Merging strategies to progressively reduce the tokens of input image and text improving model inference speed and reducing memory footprint. PuMer learns to keep salient image tokens related to the input text and merges similar textual and visual tokens by adding lightweight token reducer modules at several cross45;modal layers in the VL model. Training PuMer is mostly the same as finetuning the original VL model but faster. Our evaluation for two vision language models on four downstream VL tasks shows PuMer increases inference throughput by up to 2x and reduces memory footprint by over 5037; while incurring less than a 137; accuracy drop.
