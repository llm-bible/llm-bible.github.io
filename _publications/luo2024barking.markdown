---
layout: publication
title: 'Barking Up The Syntactic Tree: Enhancing VLM Training With Syntactic Losses'
authors: Jiayun Luo, Mir Rayat Imtiaz Hossain, Boyang Li, Leonid Sigal
conference: "Arxiv"
year: 2024
bibkey: luo2024barking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.08110"}
tags: ['Applications', 'Model Architecture', 'Reinforcement Learning', 'Large-Scale Training', 'Training Techniques', 'Attention Mechanism', 'Multimodal Models']
---
Vision-Language Models (VLMs) implicitly learn to associate image regions
with words from large-scale training data, demonstrating an emergent capability
for grounding concepts without dense annotations[14,18,51]. However, the
coarse-grained supervision from image-caption pairs is often insufficient to
resolve ambiguities in object-concept correspondence, even with enormous data
volume. Rich semantic and syntactic structures within the text modality have
been overlooked as sources of supervision. Starting from contrastive
architectures (BLIP and ALBEF) that show strong intrinsic grounding abilities,
we propose HIerarchically STructured Learning (HIST). HIST enhances spatial
vision-language alignment without using additional human annotations, by
hierarchically decomposing captions into the constituent Subjects, Phrases, and
Composite Phrases, and enforcing entailment relation between a parent and its
children in the hierarchy. Specifically, we introduce two novel loss functions:
(1) Subject Loss, which aligns image content with the subject of the
corresponding phrase, acting as an entailment of standard contrastive/matching
losses at the Phrase level; (2) Composition Loss, to balance attention across
multiple objects. HIST is general, and can be applied to any VLM for which
attention between vision and language can be computed. Compared to baseline
VLMs, HIST achieves up to +9.8% improvement in visual grounding and +6.3% in
multi-object referring segmentation. Surprisingly, the improved spatial
grounding leads to improvements in other downstream VLM tasks: +1.1% in
image-text retrieval, and +0.2% in visual question answering.
