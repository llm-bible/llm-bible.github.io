---
layout: publication
title: An Empirical Study of End-to-End Video-Language Transformers with Masked Visual Modeling
authors: Fu Tsu-jui, Li Linjie, Gan Zhe, Lin Kevin, Wang William Yang, Wang Lijuan, Liu Zicheng
conference: "Arxiv"
year: 2022
bibkey: fu2022empirical
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2209.01540"}
tags: ['ARXIV', 'Model Architecture', 'Transformer']
---
Masked visual modeling (MVM) has been recently proven effective for visual pre-training. While similar reconstructive objectives on video inputs (e.g. masked frame modeling) have been explored in video-language (VidL) pre-training previous studies fail to find a truly effective MVM strategy that can largely benefit the downstream performance. In this work we systematically examine the potential of MVM in the context of VidL learning. Specifically we base our study on a fully end-to-end VIdeO-LanguagE Transformer (VIOLET) where the supervision from MVM training can be backpropagated to the video pixel space. In total eight different reconstructive targets of MVM are explored from low-level pixel values and oriented gradients to high-level depth maps optical flow discrete visual tokens and latent visual features. We conduct comprehensive experiments and provide insights into the factors leading to effective MVM training resulting in an enhanced model VIOLETv2. Empirically we show VIOLETv2 pre-trained with MVM objective achieves notable improvements on 13 VidL benchmarks ranging from video question answering video captioning to text-to-video retrieval.
