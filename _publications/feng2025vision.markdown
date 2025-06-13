---
layout: publication
title: 'Vision Remember: Alleviating Visual Forgetting In Efficient MLLM With Vision Feature Resample'
authors: Ze Feng, Jiang-jiang Liu, Sen Yang, Lingyu Xiao, Xiaofan Li, Wankou Yang, Jingdong Wang
conference: "Arxiv"
year: 2025
bibkey: feng2025vision
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2506.03928"}
tags: ['Efficiency and Optimization', 'Model Architecture', 'Attention Mechanism', 'Multimodal Models']
---
In this work, we study the Efficient Multimodal Large Language Model. Redundant vision tokens consume a significant amount of computational memory and resources. Therefore, many previous works compress them in the Vision Projector to reduce the number of vision tokens. However, simply compressing in the Vision Projector can lead to the loss of visual information, especially for tasks that rely on fine-grained spatial relationships, such as OCR and Chart \& Table Understanding. To address this problem, we propose Vision Remember, which is inserted between the LLM decoder layers to allow vision tokens to re-memorize vision features. Specifically, we retain multi-level vision features and resample them with the vision tokens that have interacted with the text token. During the resampling process, each vision token only attends to a local region in vision features, which is referred to as saliency-enhancing local attention. Saliency-enhancing local attention not only improves computational efficiency but also captures more fine-grained contextual information and spatial relationships within the region. Comprehensive experiments on multiple visual understanding benchmarks validate the effectiveness of our method when combined with various Efficient Vision Projectors, showing performance gains without sacrificing efficiency. Based on Vision Remember, LLaVA-VR with only 2B parameters is also superior to previous representative MLLMs such as Tokenpacker-HD-7B and DeepSeek-VL-7B.
