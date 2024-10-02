---
layout: publication
title: 'Mitigating Hallucinations In Large Vision-language Models (lvlms) Via Language-contrastive Decoding (LCD)'
authors: Manevich Avshalom, Tsarfaty Reut
conference: "Arxiv"
year: 2024
bibkey: manevich2024mitigating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.04664"}
tags: ['Ethics And Bias', 'Fine Tuning', 'Multimodal Models', 'Training Techniques']
---
'Large Vision-Language Models (LVLMs) are an extension of Large Language Models (LLMs) that facilitate processing both image and text inputs, expanding AI capabilities. However, LVLMs struggle with object hallucinations due to their reliance on text cues and learned object co-occurrence biases. While most research quantifies these hallucinations, mitigation strategies are still lacking. Our study introduces a Language Contrastive Decoding (LCD) algorithm that adjusts LVLM outputs based on LLM distribution confidence levels, effectively reducing object hallucinations. We demonstrate the advantages of LCD in leading LVLMs, showing up to &#37;4 improvement in POPE F1 scores and up to &#37;36 reduction in CHAIR scores on the COCO validation set, while also improving captioning quality scores. Our method effectively improves LVLMs without needing complex post-processing or retraining, and is easily applicable to different models. Our findings highlight the potential of further exploration of LVLM-specific decoding algorithms.'
