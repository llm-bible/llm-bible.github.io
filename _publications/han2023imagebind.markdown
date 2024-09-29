---
layout: publication
title: Imagebind45;llm Multi45;modality Instruction Tuning
authors: Han Jiaming, Zhang Renrui, Shao Wenqi, Gao Peng, Xu Peng, Xiao Han, Zhang Kaipeng, Liu Chris, Wen Song, Guo Ziyu, Lu Xudong, Ren Shuai, Wen Yafei, Chen Xiaoxin, Yue Xiangyu, Li Hongsheng, Qiao Yu
conference: "Arxiv"
year: 2023
bibkey: han2023imagebind
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.03905"}
  - {name: "Code", url: "https://github.com/OpenGVLab/LLaMA&#45;Adapter"}
tags: ['Attention Mechanism', 'Has Code', 'Model Architecture', 'Multimodal Models', 'Training Techniques']
---
We present ImageBind45;LLM a multi45;modality instruction tuning method of large language models (LLMs) via ImageBind. Existing works mainly focus on language and image instruction tuning different from which our ImageBind45;LLM can respond to multi45;modality conditions including audio 3D point clouds video and their embedding45;space arithmetic by only image45;text alignment training. During training we adopt a learnable bind network to align the embedding space between LLaMA and ImageBinds image encoder. Then the image features transformed by the bind network are added to word tokens of all layers in LLaMA which progressively injects visual instructions via an attention45;free and zero45;initialized gating mechanism. Aided by the joint embedding of ImageBind the simple image45;text training enables our model to exhibit superior multi45;modality instruction45;following capabilities. During inference the multi45;modality inputs are fed into the corresponding ImageBind encoders and processed by a proposed visual cache model for further cross45;modal embedding enhancement. The training45;free cache model retrieves from three million image features extracted by ImageBind which effectively mitigates the training45;inference modality discrepancy. Notably with our approach ImageBind45;LLM can respond to instructions of diverse modalities and demonstrate significant language generation quality. Code is released at https://github.com/OpenGVLab/LLaMA&#45;Adapter.
