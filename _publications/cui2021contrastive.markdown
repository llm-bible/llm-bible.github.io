---
layout: publication
title: Contrastive Vision-language Pre-training With Limited Resources
authors: Quan Cui et al.
conference: Arxiv
year: 2021
citations: 16
bibkey: cui2021contrastive
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2112.09331'}, {name: Code,
    url: 'https://github.com/zerovl/ZeroVL'}]
tags: [Pre-Training, Multimodal Models]
---
Pioneering dual-encoder pre-training works (e.g., CLIP and ALIGN) have
revealed the potential of aligning multi-modal representations with contrastive
learning. However, these works require a tremendous amount of data and
computational resources (e.g., billion-level web data and hundreds of GPUs),
which prevent researchers with limited resources from reproduction and further
exploration. To this end, we propose a stack of novel methods, which
significantly cut down the heavy resource dependency and allow us to conduct
dual-encoder multi-modal representation alignment with limited resources.
Besides, we provide a reproducible baseline of competitive results, namely
ZeroVL, with only 14M publicly accessible academic datasets and 8 V100 GPUs.
Additionally, we collect 100M web data for pre-training, and achieve comparable
or superior results than state-of-the-art methods, further proving the
effectiveness of our methods on large-scale data. We hope that this work will
provide useful data points and experience for future research in contrastive
vision-language pre-training. Code is available at
https://github.com/zerovl/ZeroVL.