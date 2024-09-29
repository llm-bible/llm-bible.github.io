---
layout: publication
title: Temporal Scaling Law for Large Language Models
authors: Xiong Yizhe, Chen Xiansheng, Ye Xin, Chen Hui, Lin Zijia, Lian Haoran, Su Zhenpeng, Niu Jianwei, Ding Guiguang
conference: "Arxiv"
year: 2024
bibkey: xiong2024temporal
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.17785"}
tags: ['Applications', 'Attention Mechanism', 'Efficiency And Optimization', 'Large Scale Training', 'Model Architecture', 'Scaling Laws', 'Training Techniques']
---
Recently Large Language Models (LLMs) have been widely adopted in a wide range of tasks leading to increasing attention towards the research on how scaling LLMs affects their performance. Existing works termed Scaling Laws have discovered that the final test loss of LLMs scales as power-laws with model size computational budget and dataset size. However the temporal change of the test loss of an LLM throughout its pre-training process remains unexplored though it is valuable in many aspects such as selecting better hyperparameters textitdirectly on the target LLM. In this paper we propose the novel concept of Temporal Scaling Law studying how the test loss of an LLM evolves as the training steps scale up. In contrast to modeling the test loss as a whole in a coarse-grained manner we break it down and dive into the fine-grained test loss of each token position and further develop a dynamic hyperbolic-law. Afterwards we derive the much more precise temporal scaling law by studying the temporal patterns of the parameters in the dynamic hyperbolic-law. Results on both in-distribution (ID) and out-of-distribution (OOD) validation datasets demonstrate that our temporal scaling law accurately predicts the test loss of LLMs across training steps. Our temporal scaling law has broad practical applications. First it enables direct and efficient hyperparameter selection on the target LLM such as data mixture proportions. Secondly viewing the LLM pre-training dynamics from the token position granularity provides some insights to enhance the understanding of LLM pre-training.
