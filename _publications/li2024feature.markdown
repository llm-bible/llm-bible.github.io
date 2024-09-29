---
layout: publication
title: "FSMR: A Feature Swapping Multi-modal Reasoning Approach With Joint Textual And Visual Clues"
authors: Li Shuang, Wang Jiahua, Wen Lijie
conference: "Arxiv"
year: 2024
bibkey: li2024feature
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.20026"}
tags: ['Attention Mechanism', 'Model Architecture', 'Multimodal Models', 'RAG', 'Training Techniques', 'Transformer']
---
Multi-modal reasoning plays a vital role in bridging the gap between textual and visual information enabling a deeper understanding of the context. This paper presents the Feature Swapping Multi-modal Reasoning (FSMR) model designed to enhance multi-modal reasoning through feature swapping. FSMR leverages a pre-trained visual-language model as an encoder accommodating both text and image inputs for effective feature representation from both modalities. It introduces a unique feature swapping module enabling the exchange of features between identified objects in images and corresponding vocabulary words in text thereby enhancing the models comprehension of the interplay between images and text. To further bolster its multi-modal alignment capabilities FSMR incorporates a multi-modal cross-attention mechanism facilitating the joint modeling of textual and visual information. During training we employ image-text matching and cross-entropy losses to ensure semantic consistency between visual and language elements. Extensive experiments on the PMR dataset demonstrate FSMRs superiority over state-of-the-art baseline models across various performance metrics.
