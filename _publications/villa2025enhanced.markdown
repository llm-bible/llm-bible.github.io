---
layout: publication
title: 'EAGLE: Enhanced Visual Grounding Minimizes Hallucinations In Instructional Multimodal Models'
authors: Andrés Villa, Juan León Alcázar, Motasem Alfarra, Vladimir Araujo, Alvaro Soto, Bernard Ghanem
conference: "Arxiv"
year: 2025
bibkey: villa2025enhanced
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.02699"}
tags: ['Multimodal Models', 'Training Techniques', 'Model Architecture', 'Merging', 'Pretraining Methods', 'Transformer', 'Pre-Training']
---
Large language models and vision transformers have demonstrated impressive
zero-shot capabilities, enabling significant transferability in downstream
tasks. The fusion of these models has resulted in multi-modal architectures
with enhanced instructional capabilities. Despite incorporating vast image and
language pre-training, these multi-modal architectures often generate responses
that deviate from the ground truth in the image data. These failure cases are
known as hallucinations. Current methods for mitigating hallucinations
generally focus on regularizing the language component, improving the fusion
module, or ensembling multiple visual encoders to improve visual
representation. In this paper, we address the hallucination issue by directly
enhancing the capabilities of the visual component. Our approach, named EAGLE,
is fully agnostic to the LLM or fusion module and works as a post-pretraining
approach that improves the grounding and language alignment of the visual
encoder. We show that a straightforward reformulation of the original
contrastive pre-training task results in an improved visual encoder that can be
incorporated into the instructional multi-modal architecture without additional
instructional training. As a result, EAGLE achieves a significant reduction in
hallucinations across multiple challenging benchmarks and tasks.
