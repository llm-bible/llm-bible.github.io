---
layout: publication
title: 'Imageref-vl: Enabling Contextual Image Referencing In Vision-language Models'
authors: Jingwei Yi, Junhao Yin, Ju Xu, Peng Bao, Yongliang Wang, Wei Fan, Hao Wang
conference: "Arxiv"
year: 2025
bibkey: yi2025imageref
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.12418"}
  - {name: "Code", url: "https://github.com/bytedance/ImageRef-VL"}
tags: ['Fine-Tuning', 'RAG', 'Training Techniques', 'Has Code', 'Pretraining Methods', 'Multimodal Models']
---
Vision-Language Models (VLMs) have demonstrated remarkable capabilities in
understanding multimodal inputs and have been widely integrated into
Retrieval-Augmented Generation (RAG) based conversational systems. While
current VLM-powered chatbots can provide textual source references in their
responses, they exhibit significant limitations in referencing contextually
relevant images during conversations. In this paper, we introduce Contextual
Image Reference -- the ability to appropriately reference relevant images from
retrieval documents based on conversation context -- and systematically
investigate VLMs' capability in this aspect. We conduct the first evaluation
for contextual image referencing, comprising a dedicated testing dataset and
evaluation metrics. Furthermore, we propose ImageRef-VL, a method that
significantly enhances open-source VLMs' image referencing capabilities through
instruction fine-tuning on a large-scale, manually curated multimodal
conversation dataset. Experimental results demonstrate that ImageRef-VL not
only outperforms proprietary models but also achieves an 88% performance
improvement over state-of-the-art open-source VLMs in contextual image
referencing tasks. Our code is available at
https://github.com/bytedance/ImageRef-VL.
