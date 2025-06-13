---
layout: publication
title: 'Mixpert: Mitigating Multimodal Learning Conflicts With Efficient Mixture-of-vision-experts'
authors: Xin He, Xumeng Han, Longhui Wei, Lingxi Xie, Qi Tian
conference: "Arxiv"
year: 2025
bibkey: he2025mitigating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.24541"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Multimodal Models', 'Model Architecture', 'RAG', 'Pretraining Methods', 'Fine-Tuning']
---
Multimodal large language models (MLLMs) require a nuanced interpretation of complex image information, typically leveraging a vision encoder to perceive various visual scenarios. However, relying solely on a single vision encoder to handle diverse task domains proves difficult and inevitably leads to conflicts. Recent work enhances data perception by directly integrating multiple domain-specific vision encoders, yet this structure adds complexity and limits the potential for joint optimization. In this paper, we introduce Mixpert, an efficient mixture-of-vision-experts architecture that inherits the joint learning advantages from a single vision encoder while being restructured into a multi-expert paradigm for task-specific fine-tuning across different visual tasks. Additionally, we design a dynamic routing mechanism that allocates input images to the most suitable visual expert. Mixpert effectively alleviates domain conflicts encountered by a single vision encoder in multi-task learning with minimal additional computational cost, making it more efficient than multiple encoders. Furthermore, Mixpert integrates seamlessly into any MLLM, with experimental results demonstrating substantial performance gains across various tasks.
