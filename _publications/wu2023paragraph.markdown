---
layout: publication
title: 'Paragraph-to-image Generation With Information-enriched Diffusion Model'
authors: Weijia Wu, Zhuang Li, Yefei He, Mike Zheng Shou, Chunhua Shen, Lele Cheng, Yan Li, Tingting Gao, Di Zhang
conference: "IJCV 2025"
year: 2023
bibkey: wu2023paragraph
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.14284"}
tags: ['Multimodal Models', 'Training Techniques', 'Tools', 'RAG', 'Merging', 'Pretraining Methods', 'Fine-Tuning', 'Prompting']
---
Text-to-image (T2I) models have recently experienced rapid development,
achieving astonishing performance in terms of fidelity and textual alignment
capabilities. However, given a long paragraph (up to 512 words), these
generation models still struggle to achieve strong alignment and are unable to
generate images depicting complex scenes. In this paper, we introduce an
information-enriched diffusion model for paragraph-to-image generation task,
termed ParaDiffusion, which delves into the transference of the extensive
semantic comprehension capabilities of large language models to the task of
image generation. At its core is using a large language model (e.g., Llama V2)
to encode long-form text, followed by fine-tuning with LORA to alignthe
text-image feature spaces in the generation task. To facilitate the training of
long-text semantic alignment, we also curated a high-quality paragraph-image
pair dataset, namely ParaImage. This dataset contains a small amount of
high-quality, meticulously annotated data, and a large-scale synthetic dataset
with long text descriptions being generated using a vision-language model.
Experiments demonstrate that ParaDiffusion outperforms state-of-the-art models
(SD XL, DeepFloyd IF) on ViLG-300 and ParaPrompts, achieving up to 15% and 45%
human voting rate improvements for visual appeal and text faithfulness,
respectively. The code and dataset will be released to foster community
research on long-text alignment.
