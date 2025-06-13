---
layout: publication
title: 'COSMOS: Cross-modality Self-distillation For Vision Language Pre-training'
authors: Sanghwan Kim, Rui Xiao, Mariana-iuliana Georgescu, Stephan Alaniz, Zeynep Akata
conference: "Arxiv"
year: 2024
bibkey: kim2024cross
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.01814"}
  - {name: "Code", url: "https://github.com/ExplainableML/cosmos"}
tags: ['Pre-Training', 'Efficiency and Optimization', 'Tools', 'Model Architecture', 'Training Techniques', 'Attention Mechanism', 'Has Code', 'Pretraining Methods', 'Multimodal Models', 'Distillation']
---
Vision-Language Models (VLMs) trained with contrastive loss have achieved
significant advancements in various vision and language tasks. However, the
global nature of the contrastive loss makes VLMs focus predominantly on
foreground objects, neglecting other crucial information in the image, which
limits their effectiveness in downstream tasks. To address these challenges, we
propose COSMOS: CrOSs-MOdality Self-distillation for vision-language
pre-training that integrates a novel text-cropping strategy and cross-attention
module into a self-supervised learning framework. We create global and local
views of images and texts (i.e., multi-modal augmentations), which are
essential for self-distillation in VLMs. We further introduce a cross-attention
module, enabling COSMOS to learn comprehensive cross-modal representations
optimized via a cross-modality self-distillation loss. COSMOS consistently
outperforms previous strong baselines on various zero-shot downstream tasks,
including retrieval, classification, and semantic segmentation. Additionally,
it surpasses CLIP-based models trained on larger datasets in visual perception
and contextual understanding tasks. Code is available at
https://github.com/ExplainableML/cosmos.
