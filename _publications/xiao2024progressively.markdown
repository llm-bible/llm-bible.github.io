---
layout: publication
title: 'Palm2-vadapter: Progressively Aligned Language Model Makes A Strong Vision-language Adapter'
authors: Xiao Junfei, Xu Zheng, Yuille Alan, Yan Shen, Wang Boyu
conference: "Arxiv"
year: 2024
bibkey: xiao2024progressively
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.10896"}
tags: ['Applications', 'Efficiency And Optimization', 'Fine Tuning', 'Model Architecture', 'Multimodal Models', 'Training Techniques']
---
This paper demonstrates that a progressively aligned language model can effectively bridge frozen vision encoders and large language models (LLMs). While the fundamental architecture and pre-training methods of vision encoders and LLMs have been extensively studied, the architecture and training strategy of vision-language adapters vary significantly across recent works. Our research undertakes a thorough exploration of the state-of-the-art perceiver resampler architecture and builds a strong baseline. However, we observe that the vision-language alignment with perceiver resampler exhibits slow convergence and limited scalability with a lack of direct supervision. To address this issue, we propose PaLM2-VAdapter, employing a progressively aligned language model as the vision-language adapter. Compared to the strong baseline with perceiver resampler, our method empirically shows faster convergence, higher performance, and stronger scalability. Extensive experiments across various Visual Question Answering (VQA) and captioning tasks on both images and videos demonstrate that our model exhibits state-of-the-art visual understanding and multi-modal reasoning capabilities. Notably, our method achieves these advancements with 30~70&#37; fewer parameters than the state-of-the-art large vision-language models, marking a significant efficiency improvement.
