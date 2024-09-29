---
layout: publication
title: Ml45;mamba Efficient Multi45;modal Large Language Model Utilizing Mamba45;2
authors: Huang Wenjun, Pan Jiakai, Tang Jiahao, Ding Yanyu, Xing Yifei, Wang Yuhe, Wang Zhengzhuo, Hu Jianguo
conference: "Arxiv"
year: 2024
bibkey: huang2024ml
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.19832"}
tags: ['Attention Mechanism', 'Model Architecture', 'Multimodal Models', 'Pretraining Methods', 'Transformer']
---
Multimodal Large Language Models (MLLMs) have attracted much attention for their multifunctionality. However traditional Transformer architectures incur significant overhead due to their secondary computational complexity. To address this issue we introduce ML45;Mamba a multimodal language model which utilizes the latest and efficient Mamba45;2 model for inference. Mamba45;2 is known for its linear scalability and fast processing of long sequences. We replace the Transformer45;based backbone with a pre45;trained Mamba45;2 model and explore methods for integrating 2D visual selective scanning mechanisms into multimodal learning while also trying various visual encoders and Mamba45;2 model variants. Our extensive experiments in various multimodal benchmark tests demonstrate the competitive performance of ML45;Mamba and highlight the potential of state space models in multimodal tasks. The experimental results show that (1) we empirically explore how to effectively apply the 2D vision selective scan mechanism for multimodal learning. We propose a novel multimodal connector called the Mamba45;2 Scan Connector (MSC) which enhances representational capabilities. (2) ML45;Mamba achieves performance comparable to state45;of45;the45;art methods such as TinyLaVA and MobileVLM v2 through its linear sequential modeling while faster inference speed; (3) Compared to multimodal models utilizing Mamba45;1 the Mamba45;245;based ML45;Mamba exhibits superior inference performance and effectiveness.
