---
layout: publication
title: Core Context45;regularized Text Embedding Learning For Text45;to45;image Personalization
authors: Wu Feize, Pang Yun, Zhang Junyi, Pang Lianyu, Yin Jian, Zhao Baoquan, Li Qing, Mao Xudong
conference: "Arxiv"
year: 2024
bibkey: wu2024context
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.15914"}
tags: ['Efficiency And Optimization', 'Multimodal Models', 'Prompting', 'Reinforcement Learning']
---
Recent advances in text45;to45;image personalization have enabled high45;quality and controllable image synthesis for user45;provided concepts. However existing methods still struggle to balance identity preservation with text alignment. Our approach is based on the fact that generating prompt45;aligned images requires a precise semantic understanding of the prompt which involves accurately processing the interactions between the new concept and its surrounding context tokens within the CLIP text encoder. To address this we aim to embed the new concept properly into the input embedding space of the text encoder allowing for seamless integration with existing tokens. We introduce Context Regularization (CoRe) which enhances the learning of the new concepts text embedding by regularizing its context tokens in the prompt. This is based on the insight that appropriate output vectors of the text encoder for the context tokens can only be achieved if the new concepts text embedding is correctly learned. CoRe can be applied to arbitrary prompts without requiring the generation of corresponding images thus improving the generalization of the learned text embedding. Additionally CoRe can serve as a test45;time optimization technique to further enhance the generations for specific prompts. Comprehensive experiments demonstrate that our method outperforms several baseline methods in both identity preservation and text alignment. Code will be made publicly available.
