---
layout: publication
title: 'Robustness In Both Domains: CLIP Needs A Robust Text Encoder'
authors: Elias Abad Rocamora, Christian Schlarmann, Naman Deep Singh, Yongtao Wu, Matthias Hein, Volkan Cevher
conference: "Arxiv"
year: 2025
bibkey: rocamora2025robustness
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2506.03355'}
tags: ['Efficiency and Optimization', 'Multimodal Models', 'Security', 'Merging']
---
Adversarial input attacks can cause a significant shift of CLIP embeddings. This can affect the downstream robustness of models incorporating CLIP in the pipeline, such as text-to-image generative models or large vision language models. While some efforts have been done towards making the CLIP image encoders robust, the robustness of text encoders remains unexplored. In this work, we cover this gap in the literature. We propose LEAF: an efficient adversarial finetuning method for the text domain, with the ability to scale to large CLIP models. Our models significantly improve the zero-shot adversarial accuracy in the text domain, while maintaining the vision performance provided by robust image encoders. When combined with text-to-image diffusion models, we can improve the generation quality under adversarial noise. When employing our robust CLIP encoders in multimodal retrieval tasks, we improve the recall under adversarial noise over standard CLIP models. Finally, we show that robust text encoders facilitate better reconstruction of input text from its embedding via direct optimization.
