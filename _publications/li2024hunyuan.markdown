---
layout: publication
title: 'Hunyuan-dit: A Powerful Multi-resolution Diffusion Transformer With Fine-grained Chinese Understanding'
authors: Zhimin Li, Jianwei Zhang, Qin Lin, Jiangfeng Xiong, Yanxin Long, Xinchi Deng, Yingfang Zhang, Xingchao Liu, Minbin Huang, Zedong Xiao, Dayou Chen, Jiajun He, Jiahao Li, Wenyue Li, Chen Zhang, Rongwei Quan, Jianxiang Lu, Jiabin Huang, Xiaoyan Yuan, Xiaoxiao Zheng, Yixuan Li, Jihong Zhang, Chao Zhang, Meng Chen, Jie Liu, Zheng Fang, Weiyan Wang, Jinbao Xue, Yangyu Tao, Jianchen Zhu, Kai Liu, Sihuan Lin, Yifu Sun, Yun Li, Dongdong Wang, Mingtao Chen, Zhichao Hu, Xiao Xiao, Yan Chen, Yuhong Liu, Wei Liu, Di Wang, Yong Yang, Jie Jiang, Qinglin Lu
conference: "Arxiv"
year: 2024
bibkey: li2024hunyuan
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2405.08748'}
tags: ['Transformer', 'Efficiency and Optimization', 'Model Architecture', 'Merging', 'Multimodal Models', 'Pretraining Methods']
---
We present Hunyuan-DiT, a text-to-image diffusion transformer with
fine-grained understanding of both English and Chinese. To construct
Hunyuan-DiT, we carefully design the transformer structure, text encoder, and
positional encoding. We also build from scratch a whole data pipeline to update
and evaluate data for iterative model optimization. For fine-grained language
understanding, we train a Multimodal Large Language Model to refine the
captions of the images. Finally, Hunyuan-DiT can perform multi-turn multimodal
dialogue with users, generating and refining images according to the context.
Through our holistic human evaluation protocol with more than 50 professional
human evaluators, Hunyuan-DiT sets a new state-of-the-art in Chinese-to-image
generation compared with other open-source models. Code and pretrained models
are publicly available at github.com/Tencent/HunyuanDiT
