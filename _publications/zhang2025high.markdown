---
layout: publication
title: 'Repcali: High Efficient Fine-tuning Via Representation Calibration In Latent Space For Pre-trained Language Models'
authors: Fujun Zhang, Xiaoying Fan, Xiangdong Su, Guanglai Gao
conference: "Arxiv"
year: 2025
bibkey: zhang2025high
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.08463'}
tags: ['Training Techniques', 'Fine-Tuning', 'Model Architecture', 'Pretraining Methods']
---
Fine-tuning pre-trained language models (PLMs) has become a dominant paradigm in applying PLMs to downstream tasks. However, with limited fine-tuning, PLMs still struggle with the discrepancies between the representation obtained from the PLMs' encoder and the optimal input to the PLMs' decoder. This paper tackles this challenge by learning to calibrate the representation of PLMs in the latent space. In the proposed representation calibration method (RepCali), we integrate a specific calibration block to the latent space after the encoder and use the calibrated output as the decoder input. The merits of the proposed RepCali include its universality to all PLMs with encoder-decoder architectures, its plug-and-play nature, and ease of implementation. Extensive experiments on 25 PLM-based models across 8 tasks (including both English and Chinese datasets) demonstrate that the proposed RepCali offers desirable enhancements to PLMs (including LLMs) and significantly improves the performance of downstream tasks. Comparison experiments across 4 benchmark tasks indicate that RepCali is superior to the representative fine-tuning baselines.
