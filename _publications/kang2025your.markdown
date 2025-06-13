---
layout: publication
title: 'Your Large Vision-language Model Only Needs A Few Attention Heads For Visual Grounding'
authors: Seil Kang, Jinyeong Kim, Junhyeok Kim, Seong Jae Hwang
conference: "Arxiv"
year: 2025
bibkey: kang2025your
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.06287"}
tags: ['Fine-Tuning', 'Tools', 'Model Architecture', 'Training Techniques', 'Attention Mechanism', 'Pretraining Methods', 'Multimodal Models']
---
Visual grounding seeks to localize the image region corresponding to a
free-form text description. Recently, the strong multimodal capabilities of
Large Vision-Language Models (LVLMs) have driven substantial improvements in
visual grounding, though they inevitably require fine-tuning and additional
model components to explicitly generate bounding boxes or segmentation masks.
However, we discover that a few attention heads in frozen LVLMs demonstrate
strong visual grounding capabilities. We refer to these heads, which
consistently capture object locations related to text semantics, as
localization heads. Using localization heads, we introduce a straightforward
and effective training-free visual grounding framework that utilizes
text-to-image attention maps from localization heads to identify the target
objects. Surprisingly, only three out of thousands of attention heads are
sufficient to achieve competitive localization performance compared to existing
LVLM-based visual grounding methods that require fine-tuning. Our findings
suggest that LVLMs can innately ground objects based on a deep comprehension of
the text-image relationship, as they implicitly focus on relevant image regions
to generate informative text outputs. All the source codes will be made
available to the public.
