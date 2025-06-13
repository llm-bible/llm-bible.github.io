---
layout: publication
title: 'Med-2e3: A 2d-enhanced 3D Medical Multimodal Large Language Model'
authors: Yiming Shi, Xun Zhu, Ying Hu, Chenyi Guo, Miao Li, Ji Wu
conference: "Arxiv"
year: 2024
bibkey: shi2024med
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2411.12783'}
tags: ['Attention Mechanism', 'RAG', 'Applications', 'Model Architecture', 'Multimodal Models']
---
The analysis of 3D medical images is crucial for modern healthcare, yet
traditional task-specific models are becoming increasingly inadequate due to
limited generalizability across diverse clinical scenarios. Multimodal large
language models (MLLMs) offer a promising solution to these challenges.
However, existing MLLMs have limitations in fully leveraging the rich,
hierarchical information embedded in 3D medical images. Inspired by clinical
practice, where radiologists focus on both 3D spatial structure and 2D planar
content, we propose Med-2E3, a novel MLLM for 3D medical image analysis that
integrates 3D and 2D encoders. To aggregate 2D features more effectively, we
design a Text-Guided Inter-Slice (TG-IS) scoring module, which scores the
attention of each 2D slice based on slice contents and task instructions. To
the best of our knowledge, Med-2E3 is the first MLLM to integrate both 3D and
2D features for 3D medical image analysis. Experiments on a large-scale,
open-source 3D medical multimodal benchmark demonstrate that Med-2E3 exhibits
task-specific attention distribution and significantly outperforms current
state-of-the-art models, with a 14% improvement in report generation and a 5%
gain in medical visual question answering (VQA), highlighting the model's
potential in addressing complex multimodal clinical tasks. The code will be
released upon acceptance.
