---
layout: publication
title: 'MC$^2$: Multi-concept Guidance For Customized Multi-concept Generation'
authors: Jiang Jiaxiu, Zhang Yabo, Feng Kailai, Wu Xiaohe, Zuo Wangmeng
conference: "Arxiv"
year: 2024
bibkey: jiang2024multi
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.05268"}
  - {name: "Code", url: "https://github.com/JIANGJiaXiu/MC-2"}
tags: ['Applications', 'Attention Mechanism', 'Efficiency And Optimization', 'Has Code', 'Model Architecture', 'Prompting', 'Training Techniques']
---
Customized text-to-image generation aims to synthesize instantiations of user-specified concepts and has achieved unprecedented progress in handling individual concept. However when extending to multiple customized concepts existing methods exhibit limitations in terms of flexibility and fidelity only accommodating the combination of limited types of models and potentially resulting in a mix of characteristics from different concepts. In this paper we introduce the Multi-concept guidance for Multi-concept customization termed MC^2 for improved flexibility and fidelity. MC^2 decouples the requirements for model architecture via inference time optimization allowing the integration of various heterogeneous single-concept customized models. It adaptively refines the attention weights between visual and textual tokens directing image regions to focus on their associated words while diminishing the impact of irrelevant ones. Extensive experiments demonstrate that MC^2 even surpasses previous methods that require additional training in terms of consistency with input prompt and reference images. Moreover MC^2 can be extended to elevate the compositional capabilities of text-to-image generation yielding appealing results. Code will be publicly available at https://github.com/JIANGJiaXiu/MC-2."
