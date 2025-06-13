---
layout: publication
title: 'Eligen: Entity-level Controlled Image Generation With Regional Attention'
authors: Hong Zhang, Zhongjie Duan, Xingjun Wang, Yingda Chen, Yu Zhang
conference: "Arxiv"
year: 2025
bibkey: zhang2025entity
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.01097"}
  - {name: "Code", url: "https://github.com/modelscope/DiffSynth-Studio.git"}
tags: ['Model Architecture', 'Tools', 'Merging', 'Pretraining Methods', 'Transformer', 'Fine-Tuning', 'Has Code', 'Prompting', 'Attention Mechanism']
---
Recent advancements in diffusion models have significantly advanced
text-to-image generation, yet global text prompts alone remain insufficient for
achieving fine-grained control over individual entities within an image. To
address this limitation, we present EliGen, a novel framework for Entity-level
controlled image Generation. Firstly, we put forward regional attention, a
mechanism for diffusion transformers that requires no additional parameters,
seamlessly integrating entity prompts and arbitrary-shaped spatial masks. By
contributing a high-quality dataset with fine-grained spatial and semantic
entity-level annotations, we train EliGen to achieve robust and accurate
entity-level manipulation, surpassing existing methods in both spatial
precision and image quality. Additionally, we propose an inpainting fusion
pipeline, extending its capabilities to multi-entity image inpainting tasks. We
further demonstrate its flexibility by integrating it with other open-source
models such as IP-Adapter, In-Context LoRA and MLLM, unlocking new creative
possibilities. The source code, model, and dataset are published at
https://github.com/modelscope/DiffSynth-Studio.git.
