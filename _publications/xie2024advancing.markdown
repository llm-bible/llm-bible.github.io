---
layout: publication
title: Advancing Multimodal Large Language Models With Quantization45;aware Scale Learning For Efficient Adaptation
authors: Xie Jingjing, Zhang Yuxin, Lin Mingbao, Cao Liujuan, Ji Rongrong
conference: "Arxiv"
year: 2024
bibkey: xie2024advancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.03735"}
  - {name: "Code", url: "https://github.com/xjjxmu/QSLAW"}
tags: ['Efficiency And Optimization', 'Has Code', 'Multimodal Models', 'Quantization', 'Training Techniques']
---
This paper presents the first study to explore the potential of parameter quantization for multimodal large language models to alleviate the significant resource constraint encountered during vision45;language instruction tuning. We introduce a Quantization45;aware Scale LeArning method based on multimodal Warmup termed QSLAW. This method is grounded in two key innovations (1) The learning of group45;wise scale factors for quantized LLM weights to mitigate the quantization error arising from activation outliers and achieve more effective vision45;language instruction tuning; (2) The implementation of a multimodal warmup that progressively integrates linguistic and multimodal training samples thereby preventing overfitting of the quantized model to multimodal data while ensuring stable adaptation of multimodal large language models to downstream vision45;language tasks. Extensive experiments demonstrate that models quantized by QSLAW perform on par with or even surpass their full45;precision counterparts while facilitating up to 1.4 times reduction in VL tuning time and GPU consumption. Our code is released at https://github.com/xjjxmu/QSLAW.
