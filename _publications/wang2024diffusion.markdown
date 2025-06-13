---
layout: publication
title: 'Diffusion Feedback Helps CLIP See Better'
authors: Wenxuan Wang, Quan Sun, Fan Zhang, Yepeng Tang, Jing Liu, Xinlong Wang
conference: "Arxiv"
year: 2024
bibkey: wang2024diffusion
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.20171"}
  - {name: "Code", url: "https://github.com/baaivision/DIVA"}
tags: ['Multimodal Models', 'Training Techniques', 'Tools', 'Reinforcement Learning', 'RAG', 'Merging', 'Ethics and Bias', 'Has Code', 'Pre-Training']
---
Contrastive Language-Image Pre-training (CLIP), which excels at abstracting
open-world representations across domains and modalities, has become a
foundation for a variety of vision and multimodal tasks. However, recent
studies reveal that CLIP has severe visual shortcomings, such as which can
hardly distinguish orientation, quantity, color, structure, etc. These visual
shortcomings also limit the perception capabilities of multimodal large
language models (MLLMs) built on CLIP. The main reason could be that the
image-text pairs used to train CLIP are inherently biased, due to the lack of
the distinctiveness of the text and the diversity of images. In this work, we
present a simple post-training approach for CLIP models, which largely
overcomes its visual shortcomings via a self-supervised diffusion process. We
introduce DIVA, which uses the DIffusion model as a Visual Assistant for CLIP.
Specifically, DIVA leverages generative feedback from text-to-image diffusion
models to optimize CLIP representations, with only images (without
corresponding text). We demonstrate that DIVA improves CLIP's performance on
the challenging MMVP-VLM benchmark which assesses fine-grained visual abilities
to a large extent (e.g., 3-7%), and enhances the performance of MLLMs and
vision models on multimodal understanding and segmentation tasks. Extensive
evaluation on 29 image classification and retrieval benchmarks confirms that
our framework preserves CLIP's strong zero-shot capabilities. The code is
available at https://github.com/baaivision/DIVA.
