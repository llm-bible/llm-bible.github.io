---
layout: publication
title: 'Audio-visual LLM For Video Understanding'
authors: Fangxun Shu, Lei Zhang, Hao Jiang, Cihang Xie
conference: "Arxiv"
year: 2023
bibkey: shu2023audio
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.06720"}
tags: ['GPT', 'Training Techniques', 'Multimodal Models', 'Model Architecture']
---
This paper presents Audio-Visual LLM, a Multimodal Large Language Model that
takes both visual and auditory inputs for holistic video understanding. A key
design is the modality-augmented training, which involves the integration of
modality-specific tokens engineered to activate the appropriate visual and/or
auditory encoder selectively. This mechanism is pivotal in enabling end-to-end
joint training with video data at different modalities, including visual-only,
audio-only, and audio-visual formats. Moreover, we introduce a high-quality
video instruction dataset, derived from GPT-4. This dataset allows Audio-Visual
LLM to adeptly process a variety of task-oriented video instructions, ranging
from multi-turn conversations and audio-visual narratives to complex reasoning
tasks. Extensive experiments demonstrate that Audio-Visual LLM impressively
achieves strong zero-shot results across a range of video understanding tasks.
For example, Audio-Visual LLM achieves an accuracy of 53.7% on MSRVTT-QA,
outperforming non-LLM-based InterVideo by 6.6% and LLM-based Valley by 4.4%,
respectively. Additionally, our Audio-Visual LLM also achieves competitive
performance on audio tasks (e.g., AudioCaps).
