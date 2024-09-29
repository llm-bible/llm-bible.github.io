---
layout: publication
title: CogVLM Visual Expert for Pretrained Language Models
authors: Wang Weihan, Lv Qingsong, Yu Wenmeng, Hong Wenyi, Qi Ji, Wang Yan, Ji Junhui, Yang Zhuoyi, Zhao Lei, Song Xixuan, Xu Jiazheng, Xu Bin, Li Juanzi, Dong Yuxiao, Ding Ming, Tang Jie
conference: "Arxiv"
year: 2023
bibkey: wang2023cogvlm
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.03079"}
  - {name: "Code", url: "https://github.com/THUDM/CogVLM"}
tags: ['Attention Mechanism', 'Has Code', 'Merging', 'Model Architecture', 'Multimodal Models']
---
We introduce CogVLM a powerful open-source visual language foundation model. Different from the popular shallow alignment method which maps image features into the input space of language model CogVLM bridges the gap between the frozen pretrained language model and image encoder by a trainable visual expert module in the attention and FFN layers. As a result CogVLM enables deep fusion of vision language features without sacrificing any performance on NLP tasks. CogVLM-17B achieves state-of-the-art performance on 10 classic cross-modal benchmarks including NoCaps Flicker30k captioning RefCOCO RefCOCO+ RefCOCOg Visual7W GQA ScienceQA VizWiz VQA and TDIUC and ranks the 2nd on VQAv2 OKVQA TextVQA COCO captioning etc. surpassing or matching PaLI-X 55B. Codes and checkpoints are available at https://github.com/THUDM/CogVLM.
