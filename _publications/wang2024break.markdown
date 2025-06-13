---
layout: publication
title: 'Break The Visual Perception: Adversarial Attacks Targeting Encoded Visual Tokens Of Large Vision-language Models'
authors: Yubo Wang, Chaohu Liu, Yanqiu Qu, Haoyu Cao, Deqiang Jiang, Linli Xu
conference: "Arxiv"
year: 2024
bibkey: wang2024break
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.06699"}
tags: ['Security', 'Multimodal Models', 'Reinforcement Learning']
---
Large vision-language models (LVLMs) integrate visual information into large
language models, showcasing remarkable multi-modal conversational capabilities.
However, the visual modules introduces new challenges in terms of robustness
for LVLMs, as attackers can craft adversarial images that are visually clean
but may mislead the model to generate incorrect answers. In general, LVLMs rely
on vision encoders to transform images into visual tokens, which are crucial
for the language models to perceive image contents effectively. Therefore, we
are curious about one question: Can LVLMs still generate correct responses when
the encoded visual tokens are attacked and disrupting the visual information?
To this end, we propose a non-targeted attack method referred to as VT-Attack
(Visual Tokens Attack), which constructs adversarial examples from multiple
perspectives, with the goal of comprehensively disrupting feature
representations and inherent relationships as well as the semantic properties
of visual tokens output by image encoders. Using only access to the image
encoder in the proposed attack, the generated adversarial examples exhibit
transferability across diverse LVLMs utilizing the same image encoder and
generality across different tasks. Extensive experiments validate the superior
attack performance of the VT-Attack over baseline methods, demonstrating its
effectiveness in attacking LVLMs with image encoders, which in turn can provide
guidance on the robustness of LVLMs, particularly in terms of the stability of
the visual feature space.
