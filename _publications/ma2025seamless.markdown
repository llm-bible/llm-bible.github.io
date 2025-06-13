---
layout: publication
title: 'X2I: Seamless Integration Of Multimodal Understanding Into Diffusion Transformer Via Attention Distillation'
authors: Jian Ma, Qirong Peng, Xu Guo, Chen Chen, Haonan Lu, Zhenyu Yang
conference: "Arxiv"
year: 2025
bibkey: ma2025seamless
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.06134'}
  - {name: "Code", url: 'https://github.com/OPPO-Mente-Lab/X2I'}
tags: ['Attention Mechanism', 'Has Code', 'Transformer', 'Efficiency and Optimization', 'Distillation', 'Model Architecture', 'Tools', 'Training Techniques', 'Fine-Tuning', 'Merging', 'Multimodal Models', 'Reinforcement Learning', 'Pretraining Methods']
---
Text-to-image (T2I) models are well known for their ability to produce highly
realistic images, while multimodal large language models (MLLMs) are renowned
for their proficiency in understanding and integrating multiple modalities.
However, currently there is no straightforward and efficient framework to
transfer the multimodal comprehension abilities of MLLMs to T2I models to
enable them to understand multimodal inputs. In this paper, we propose the X2I
framework, which endows Diffusion Transformer (DiT) models with the capability
to comprehend various modalities, including multilingual text, screenshot
documents, images, videos, and audio. X2I is trained using merely 100K English
corpus with 160 GPU hours. Building on the DiT teacher model, we adopt an
innovative distillation method to extract the inference capabilities of the
teacher model and design a lightweight AlignNet structure to serve as an
intermediate bridge. Compared to the teacher model, X2I shows a decrease in
performance degradation of less than 1% while gaining various multimodal
understanding abilities, including multilingual to image, image to image,
image-text to image, video to image, audio to image, and utilizing creative
fusion to enhance imagery. Furthermore, it is applicable for LoRA training in
the context of image-text to image generation, filling a void in the industry
in this area. We further design a simple LightControl to enhance the fidelity
of instructional image editing. Finally, extensive experiments demonstrate the
effectiveness, efficiency, multifunctionality, and transferability of our X2I.
The open-source code and checkpoints for X2I can be found at the following
link: https://github.com/OPPO-Mente-Lab/X2I.
