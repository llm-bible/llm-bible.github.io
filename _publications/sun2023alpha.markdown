---
layout: publication
title: 'Alpha-clip: A CLIP Model Focusing On Wherever You Want'
authors: Zeyi Sun et al.
conference: Arxiv
year: 2023
citations: 21
bibkey: sun2023alpha
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2312.03818'}]
tags: [Pre-Training, Multimodal Models]
---
Contrastive Language-Image Pre-training (CLIP) plays an essential role in
extracting valuable content information from images across diverse tasks. It
aligns textual and visual modalities to comprehend the entire image, including
all the details, even those irrelevant to specific tasks. However, for a finer
understanding and controlled editing of images, it becomes crucial to focus on
specific regions of interest, which can be indicated as points, masks, or boxes
by humans or perception models. To fulfill the requirements, we introduce
Alpha-CLIP, an enhanced version of CLIP with an auxiliary alpha channel to
suggest attentive regions and fine-tuned with constructed millions of RGBA
region-text pairs. Alpha-CLIP not only preserves the visual recognition ability
of CLIP but also enables precise control over the emphasis of image contents.
It demonstrates effectiveness in various tasks, including but not limited to
open-world recognition, multimodal large language models, and conditional 2D /
3D generation. It has a strong potential to serve as a versatile tool for
image-related tasks.