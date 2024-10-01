---
layout: publication
title: 'Learn To Be Efficient: Build Structured Sparsity In Large Language Models'
authors: Zheng Haizhong, Bai Xiaoyan, Liu Xueshen, Mao Z. Morley, Chen Beidi, Lai Fan, Prakash Atul
conference: "Arxiv"
year: 2024
bibkey: zheng2024learn
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.06126"}
tags: ['Efficiency And Optimization', 'Ethics And Bias', 'Reinforcement Learning', 'Training Techniques']
---
'Large Language Models (LLMs) have achieved remarkable success with their billion-level parameters, yet they incur high inference overheads. The emergence of activation sparsity in LLMs provides a natural approach to reduce this cost by involving only parts of the parameters for inference. However, existing methods only focus on utilizing this naturally formed activation sparsity in a post-training setting, overlooking the potential for further amplifying this inherent sparsity. In this paper, we hypothesize that LLMs can learn to be efficient by achieving more structured activation sparsity. To achieve this, we introduce a novel training algorithm, Learn-To-be-Efficient (LTE), designed to train efficiency-aware LLMs to learn to activate fewer neurons and achieve a better trade-off between sparsity and performance. Furthermore, unlike SOTA MoEfication methods, which mainly focus on ReLU-based models, LTE can also be applied to LLMs like LLaMA using non-ReLU activations. Extensive evaluation on language understanding, language generation, and instruction tuning tasks show that LTE consistently outperforms SOTA baselines. Along with our hardware-aware custom kernel implementation, LTE reduces LLaMA2-7B inference latency by 25&#37; at 50&#37; sparsity.'
