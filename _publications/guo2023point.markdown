---
layout: publication
title: 'Point-bind & Point-llm: Aligning Point Cloud With Multi-modality For 3D Understanding, Generation, And Instruction Following'
authors: Ziyu Guo, Renrui Zhang, Xiangyang Zhu, Yiwen Tang, Xianzheng Ma, Jiaming Han, Kexin Chen, Peng Gao, Xianzhi Li, Hongsheng Li, Pheng-ann Heng
conference: "Arxiv"
year: 2023
bibkey: guo2023point
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.00615"}
  - {name: "Code", url: "https://github.com/ZiyuGuo99/Point-Bind_Point-LLM"}
tags: ['Fine-Tuning', 'Applications', 'Reinforcement Learning', 'Training Techniques', 'Has Code', 'Pretraining Methods']
---
We introduce Point-Bind, a 3D multi-modality model aligning point clouds with
2D image, language, audio, and video. Guided by ImageBind, we construct a joint
embedding space between 3D and multi-modalities, enabling many promising
applications, e.g., any-to-3D generation, 3D embedding arithmetic, and 3D
open-world understanding. On top of this, we further present Point-LLM, the
first 3D large language model (LLM) following 3D multi-modal instructions. By
parameter-efficient fine-tuning techniques, Point-LLM injects the semantics of
Point-Bind into pre-trained LLMs, e.g., LLaMA, which requires no 3D instruction
data, but exhibits superior 3D and multi-modal question-answering capacity. We
hope our work may cast a light on the community for extending 3D point clouds
to multi-modality applications. Code is available at
https://github.com/ZiyuGuo99/Point-Bind_Point-LLM.
