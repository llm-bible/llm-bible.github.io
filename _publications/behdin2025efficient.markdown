---
layout: publication
title: 'Efficient AI In Practice: Training And Deployment Of Efficient Llms For Industry Applications'
authors: Kayhan Behdin, Yun Dai, Ata Fatahibaarzi, Aman Gupta, Qingquan Song, Shao Tang, Hejian Sang, Gregory Dexter, Sirou Zhu, Siyu Zhu, Tejas Dharamsi, Maziar Sanjabi, Vignesh Kothapalli, Hamed Firooz, Zhoutong Fu, Yihan Cao, Pin-lun Hsu, Fedor Borisyuk, Zhipeng Wang, Rahul Mazumder, Natesh Pillai, Luke Simon
conference: "Arxiv"
year: 2025
bibkey: behdin2025efficient
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.14305"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'Tools', 'Reinforcement Learning', 'Scaling Laws', 'Distillation', 'Pruning', 'Quantization', 'Large-Scale Training', 'Pre-Training', 'Applications']
---
Large language models (LLMs) have demonstrated remarkable performance across
a wide range of industrial applications, from search and recommendations to
generative tasks. Although scaling laws indicate that larger models generally
yield better generalization and performance, their substantial computational
requirements often render them impractical for many real-world scenarios at
scale. In this paper, we present methods and insights for training small
language models (SLMs) that deliver high performance and efficiency in
deployment. We focus on two key techniques: (1) knowledge distillation and (2)
model compression via quantization and pruning. These approaches enable SLMs to
retain much of the quality of their larger counterparts while significantly
reducing training, serving costs, and latency. We detail the impact of these
techniques on a variety of use cases at a large professional social network
platform and share deployment lessons - including hardware optimization
strategies that enhance speed and throughput for both predictive and
reasoning-based applications.
