---
layout: publication
title: Understanding And Improving In45;context Learning On Vision45;language Models
authors: Chen Shuo, Han Zhen, He Bailan, Buckley Mark, Torr Philip, Tresp Volker, Gu Jindong
conference: "Arxiv"
year: 2023
bibkey: chen2023understanding
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.18021"}
tags: ['Attention Mechanism', 'Model Architecture', 'Multimodal Models', 'Reinforcement Learning']
---
Recently in45;context learning (ICL) on large language models (LLMs) has received great attention and this technique can also be applied to vision45;language models (VLMs) built upon LLMs. These VLMs can respond to queries by conditioning responses on a series of multimodal demonstrations which comprise images queries and answers. Though ICL has been extensively studied on LLMs its research on VLMs remains limited. The inclusion of additional visual information in the demonstrations motivates the following research questions which of the two modalities in the demonstration is more significant How can we select effective multimodal demonstrations to enhance ICL performance This study investigates the significance of both visual and language information. Our findings indicate that ICL in VLMs is predominantly driven by the textual information in the demonstrations whereas the visual information in the demonstrations barely affects the ICL performance. Subsequently we provide an understanding of the findings by analyzing the model information flow and comparing model inner states given different ICL settings. Motivated by our analysis we propose a simple yet effective approach termed Mixed Modality In45;Context Example Selection (MMICES) which considers both visual and language modalities when selecting demonstrations and shows better ICL performance. Extensive experiments are conducted to support our findings understanding and improvement of the ICL performance of VLMs.
