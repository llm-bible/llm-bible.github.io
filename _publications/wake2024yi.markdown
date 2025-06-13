---
layout: publication
title: 'Yi-lightning Technical Report'
authors: Alan Wake, Bei Chen, C. X. Lv, Chao Li, Chengen Huang, Chenglin Cai, Chujie Zheng, Daniel Cooper, Fan Zhou, Feng Hu, Ge Zhang, Guoyin Wang, Heng Ji, Howard Qiu, Jiangcheng Zhu, Jun Tian, Katherine Su, Lihuan Zhang, Liying Li, Ming Song, Mou Li, Peng Liu, Qicheng Hu, Shawn Wang, Shijun Zhou, Shiming Yang, Shiyong Li, Tianhang Zhu, Wen Xie, Wenhao Huang, Xiang He, Xiaobo Chen, Xiaohui Hu, Xiaoyi Ren, Xinyao Niu, Yanpeng Li, Yongke Zhao, Yongzhen Luo, Yuchi Xu, Yuxuan Sha, Zhaodong Yan, Zhiyuan Liu, Zirui Zhang, Zonghong Dai
conference: "Arxiv"
year: 2024
bibkey: wake2024yi
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2412.01253'}
  - {name: "Code", url: 'https://platform.lingyiwanwu.com'}
tags: ['Has Code', 'Ethics and Bias', 'RAG', 'Tools', 'Applications', 'Model Architecture', 'Fine-Tuning', 'Training Techniques', 'Prompting', 'Reinforcement Learning', 'Pre-Training', 'Responsible AI', 'Pretraining Methods']
---
This technical report presents Yi-Lightning, our latest flagship large
language model (LLM). It achieves exceptional performance, ranking 6th overall
on Chatbot Arena, with particularly strong results (2nd to 4th place) in
specialized categories including Chinese, Math, Coding, and Hard Prompts.
Yi-Lightning leverages an enhanced Mixture-of-Experts (MoE) architecture,
featuring advanced expert segmentation and routing mechanisms coupled with
optimized KV-caching techniques. Our development process encompasses
comprehensive pre-training, supervised fine-tuning (SFT), and reinforcement
learning from human feedback (RLHF), where we devise deliberate strategies for
multi-stage training, synthetic data construction, and reward modeling.
Furthermore, we implement RAISE (Responsible AI Safety Engine), a
four-component framework to address safety issues across pre-training,
post-training, and serving phases. Empowered by our scalable super-computing
infrastructure, all these innovations substantially reduce training, deployment
and inference costs while maintaining high-performance standards. With further
evaluations on public academic benchmarks, Yi-Lightning demonstrates
competitive performance against top-tier LLMs, while we observe a notable
disparity between traditional, static benchmark results and real-world, dynamic
human preferences. This observation prompts a critical reassessment of
conventional benchmarks' utility in guiding the development of more intelligent
and powerful AI systems for practical applications. Yi-Lightning is now
available through our developer platform at https://platform.lingyiwanwu.com.
