---
layout: publication
title: 'Mindsemantix: Deciphering Brain Visual Experiences With A Brain-language Model'
authors: Ziqi Ren, Jie Li, Xuetong Xue, Xin Li, Fan Yang, Zhicheng Jiao, Xinbo Gao
conference: "Arxiv"
year: 2024
bibkey: ren2024deciphering
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2405.18812'}
tags: ['Transformer', 'Model Architecture', 'Tools', 'Training Techniques', 'Merging', 'Applications', 'Multimodal Models', 'Reinforcement Learning', 'Pretraining Methods']
---
Deciphering the human visual experience through brain activities captured by
fMRI represents a compelling and cutting-edge challenge in the field of
neuroscience research. Compared to merely predicting the viewed image itself,
decoding brain activity into meaningful captions provides a higher-level
interpretation and summarization of visual information, which naturally
enhances the application flexibility in real-world situations. In this work, we
introduce MindSemantix, a novel multi-modal framework that enables LLMs to
comprehend visually-evoked semantic content in brain activity. Our MindSemantix
explores a more ideal brain captioning paradigm by weaving LLMs into brain
activity analysis, crafting a seamless, end-to-end Brain-Language Model. To
effectively capture semantic information from brain responses, we propose
Brain-Text Transformer, utilizing a Brain Q-Former as its core architecture. It
integrates a pre-trained brain encoder with a frozen LLM to achieve multi-modal
alignment of brain-vision-language and establish a robust brain-language
correspondence. To enhance the generalizability of neural representations, we
pre-train our brain encoder on a large-scale, cross-subject fMRI dataset using
self-supervised learning techniques. MindSemantix provides more feasibility to
downstream brain decoding tasks such as stimulus reconstruction. Conditioned by
MindSemantix captioning, our framework facilitates this process by integrating
with advanced generative models like Stable Diffusion and excels in
understanding brain visual perception. MindSemantix generates high-quality
captions that are deeply rooted in the visual and semantic information derived
from brain activity. This approach has demonstrated substantial quantitative
improvements over prior art. Our code will be released.
