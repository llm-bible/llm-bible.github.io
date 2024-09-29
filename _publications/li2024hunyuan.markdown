---
layout: publication
title: Hunyuan-dit: A Powerful Multi-resolution Diffusion Transformer With Fine-grained Chinese Understanding
authors: Li Zhimin, Zhang Jianwei, Lin Qin, Xiong Jiangfeng, Long Yanxin, Deng Xinchi, Zhang Yingfang, Liu Xingchao, Huang Minbin, Xiao Zedong, Chen Dayou, He Jiajun, Li Jiahao, Li Wenyue, Zhang Chen, Quan Rongwei, Lu Jianxiang, Huang Jiabin, Yuan Xiaoyan, Zheng Xiaoxiao, Li Yixuan, Zhang Jihong, Zhang Chao, Chen Meng, Liu Jie, Fang Zheng, Wang Weiyan, Xue Jinbao, Tao Yangyu, Zhu Jianchen, Liu Kai, Lin Sihuan, Sun Yifu, Li Yun, Wang Dongdong, Chen Mingtao, Hu Zhichao, Xiao Xiao, Chen Yan, Liu Yuhong, Liu Wei, Wang Di, Yang Yong, Jiang Jie, Lu Qinglin
conference: "Arxiv"
year: 2024
bibkey: li2024hunyuan
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.08748"}
tags: ['Efficiency And Optimization', 'Merging', 'Model Architecture', 'Multimodal Models', 'Pretraining Methods', 'Transformer']
---
We present Hunyuan-DiT a text-to-image diffusion transformer with fine-grained understanding of both English and Chinese. To construct Hunyuan-DiT we carefully design the transformer structure text encoder and positional encoding. We also build from scratch a whole data pipeline to update and evaluate data for iterative model optimization. For fine-grained language understanding we train a Multimodal Large Language Model to refine the captions of the images. Finally Hunyuan-DiT can perform multi-turn multimodal dialogue with users generating and refining images according to the context. Through our holistic human evaluation protocol with more than 50 professional human evaluators Hunyuan-DiT sets a new state-of-the-art in Chinese-to-image generation compared with other open-source models. Code and pretrained models are publicly available at github.com/Tencent/HunyuanDiT
