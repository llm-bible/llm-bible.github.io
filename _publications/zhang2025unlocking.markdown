---
layout: publication
title: 'Tpcap: Unlocking Zero-shot Image Captioning With Trigger-augmented And Multi-modal Purification Modules'
authors: Ruoyu Zhang, Lulu Wang, Yi He, Tongling Pan, Zhengtao Yu, Yingna Li
conference: "Arxiv"
year: 2025
bibkey: zhang2025unlocking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.11024"}
tags: ['RAG', 'Training Techniques', 'Ethics and Bias', 'Tools']
---
Recent advancements in large language models (LLMs) have significantly
enhanced the fluency and logical coherence of image captioning.
Retrieval-Augmented Generation (RAG) is widely adopted to incorporate external
knowledge into LLMs; however, existing RAG-based methods rely on separate
retrieval banks, introducing computational overhead and limiting the
utilization of LLMs' inherent zero-shot capabilities. To address these
limitations, we propose TPCap, a novel trigger-augmented and multi-modal
purification framework for zero-shot image captioning without external
retrieval libraries. TPCap consists of two key components: trigger-augmented
(TA) generation and multi-modal purification (MP). The TA module employs a
trigger projector with frozen and learnable projections to activate LLMs'
contextual reasoning, enhance visual-textual alignment, and mitigate data bias.
The MP module further refines the generated entity-related information by
filtering noise and enhancing feature quality, ensuring more precise and
factually consistent captions. We evaluate TPCap on COCO, NoCaps, Flickr30k,
and WHOOPS datasets. With only 0.82M trainable parameters and training on a
single NVIDIA RTX 4090 GPU, TPCap achieves competitive performance comparable
to state-of-the-art models.
