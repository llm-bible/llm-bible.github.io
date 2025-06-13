---
layout: publication
title: 'Probing The Robustness Of Vision-language Pretrained Models: A Multimodal Adversarial Attack Approach'
authors: Jiwei Guan, Tianyu Ding, Longbing Cao, Lei Pan, Chen Wang, Xi Zheng
conference: "Arxiv"
year: 2024
bibkey: guan2024probing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.13461"}
tags: ['Transformer', 'Model Architecture', 'Reinforcement Learning', 'Merging', 'Security', 'Training Techniques', 'Attention Mechanism', 'Pretraining Methods', 'Multimodal Models']
---
Vision-language pretraining (VLP) with transformers has demonstrated
exceptional performance across numerous multimodal tasks. However, the
adversarial robustness of these models has not been thoroughly investigated.
Existing multimodal attack methods have largely overlooked cross-modal
interactions between visual and textual modalities, particularly in the context
of cross-attention mechanisms. In this paper, we study the adversarial
vulnerability of recent VLP transformers and design a novel Joint Multimodal
Transformer Feature Attack (JMTFA) that concurrently introduces adversarial
perturbations in both visual and textual modalities under white-box settings.
JMTFA strategically targets attention relevance scores to disrupt important
features within each modality, generating adversarial samples by fusing
perturbations and leading to erroneous model predictions. Experimental results
indicate that the proposed approach achieves high attack success rates on
vision-language understanding and reasoning downstream tasks compared to
existing baselines. Notably, our findings reveal that the textual modality
significantly influences the complex fusion processes within VLP transformers.
Moreover, we observe no apparent relationship between model size and
adversarial robustness under our proposed attacks. These insights emphasize a
new dimension of adversarial robustness and underscore potential risks in the
reliable deployment of multimodal AI systems.
