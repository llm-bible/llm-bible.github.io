---
layout: publication
title: Semantic Alignment For Multimodal Large Language Models
authors: Wu Tao, Li Mengze, Chen Jingyuan, Ji Wei, Lin Wang, Gao Jinyang, Kuang Kun, Zhao Zhou, Wu Fei
conference: "Arxiv"
year: 2024
bibkey: wu2024semantic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.12867"}
tags: ['Attention Mechanism', 'Model Architecture', 'Multimodal Models', 'Reinforcement Learning']
---
Research on Multi45;modal Large Language Models (MLLMs) towards the multi45;image cross45;modal instruction has received increasing attention and made significant progress particularly in scenarios involving closely resembling images (e.g. change captioning). Existing MLLMs typically follow a two45;step process in their pipelines first extracting visual tokens independently for each input image and then aligning these visual tokens from different images with the Large Language Model (LLM) in its textual feature space. However the independent extraction of visual tokens for each image may result in different semantics being prioritized for different images in the first step leading to a lack of preservation of linking information among images for subsequent LLM analysis. This issue becomes more serious in scenarios where significant variations exist among the images (e.g. visual storytelling). To address this challenge we introduce Semantic Alignment for Multi45;modal large language models (SAM). By involving the bidirectional semantic guidance between different images in the visual45;token extraction process SAM aims to enhance the preservation of linking information for coherent analysis and align the semantics of different images before feeding them into LLM. As the test bed we propose a large45;scale dataset named MmLINK consisting of 69K samples. Different from most existing datasets for MLLMs fine45;tuning our MmLINK dataset comprises multi45;modal instructions with significantly diverse images. Extensive experiments on the group captioning task and the storytelling task prove the effectiveness of our SAM model surpassing the state45;of45;the45;art methods by a large margin (+3737; for group captioning and +2237; for storytelling on CIDEr score). Project page https://mccartney01.github.io/SAM.
