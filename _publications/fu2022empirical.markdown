---
layout: publication
title: An Empirical Study Of End45;to45;end Video45;language Transformers With Masked Visual Modeling
authors: Fu Tsu-jui, Li Linjie, Gan Zhe, Lin Kevin, Wang William Yang, Wang Lijuan, Liu Zicheng
conference: "Arxiv"
year: 2022
bibkey: fu2022empirical
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2209.01540"}
tags: ['Applications', 'Model Architecture', 'Pretraining Methods', 'Training Techniques', 'Transformer']
---
Masked visual modeling (MVM) has been recently proven effective for visual pre45;training. While similar reconstructive objectives on video inputs (e.g. masked frame modeling) have been explored in video45;language (VidL) pre45;training previous studies fail to find a truly effective MVM strategy that can largely benefit the downstream performance. In this work we systematically examine the potential of MVM in the context of VidL learning. Specifically we base our study on a fully end45;to45;end VIdeO45;LanguagE Transformer (VIOLET) where the supervision from MVM training can be backpropagated to the video pixel space. In total eight different reconstructive targets of MVM are explored from low45;level pixel values and oriented gradients to high45;level depth maps optical flow discrete visual tokens and latent visual features. We conduct comprehensive experiments and provide insights into the factors leading to effective MVM training resulting in an enhanced model VIOLETv2. Empirically we show VIOLETv2 pre45;trained with MVM objective achieves notable improvements on 13 VidL benchmarks ranging from video question answering video captioning to text45;to45;video retrieval.
