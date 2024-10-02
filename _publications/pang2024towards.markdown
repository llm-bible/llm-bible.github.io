---
layout: publication
title: 'Attndreambooth: Towards Text-aligned Personalized Text-to-image Generation'
authors: Pang Lianyu, Yin Jian, Zhao Baoquan, Wu Feize, Wang Fu Lee, Li Qing, Mao Xudong
conference: "Arxiv"
year: 2024
bibkey: pang2024towards
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.05000"}
tags: ['Applications', 'Attention Mechanism', 'Model Architecture', 'Prompting', 'Reinforcement Learning', 'Training Techniques']
---
'Recent advances in text-to-image models have enabled high-quality personalized image synthesis of user-provided concepts with flexible textual control. In this work, we analyze the limitations of two primary techniques in text-to-image personalization: Textual Inversion and DreamBooth. When integrating the learned concept into new prompts, Textual Inversion tends to overfit the concept, while DreamBooth often overlooks it. We attribute these issues to the incorrect learning of the embedding alignment for the concept. We introduce AttnDreamBooth, a novel approach that addresses these issues by separately learning the embedding alignment, the attention map, and the subject identity in different training stages. We also introduce a cross-attention map regularization term to enhance the learning of the attention map. Our method demonstrates significant improvements in identity preservation and text alignment compared to the baseline methods.'
