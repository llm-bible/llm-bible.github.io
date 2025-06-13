---
layout: publication
title: 'Webcode2m: A Real-world Dataset For Code Generation From Webpage Designs'
authors: Yi Gui, Zhen Li, Yao Wan, Yemin Shi, Hongyu Zhang, Yi Su, Bohua Chen, Dongping Chen, Siyuan Wu, Xing Zhou, Wenbin Jiang, Hai Jin, Xiangliang Zhang
conference: "Arxiv"
year: 2024
bibkey: gui2024real
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2404.06369'}
  - {name: "Code", url: 'https://webcode2m.github.io'}
tags: ['Has Code', 'Transformer', 'Model Architecture', 'Applications', 'Tools', 'Multimodal Models', 'Reinforcement Learning', 'Pretraining Methods']
---
Automatically generating webpage code from webpage designs can significantly
reduce the workload of front-end developers, and recent Multimodal Large
Language Models (MLLMs) have shown promising potential in this area. However,
our investigation reveals that most existing MLLMs are constrained by the
absence of high-quality, large-scale, real-world datasets, resulting in
inadequate performance in automated webpage code generation. To fill this gap,
this paper introduces WebCode2M, a new dataset comprising 2.56 million
instances, each containing a design image along with the corresponding webpage
code and layout details. Sourced from real-world web resources, WebCode2M
offers a rich and valuable dataset for webpage code generation across a variety
of applications. The dataset quality is ensured by a scoring model that filters
out instances with aesthetic deficiencies or other incomplete elements. To
validate the effectiveness of WebCode2M, we introduce a baseline model based on
the Vision Transformer (ViT), named WebCoder, and establish a benchmark for
fair comparison. Additionally, we introduce a new metric, TreeBLEU, to measure
the structural hierarchy recall. The benchmarking results demonstrate that our
dataset significantly improves the ability of MLLMs to generate code from
webpage designs, confirming its effectiveness and usability for future
applications in front-end design tools. Finally, we highlight several practical
challenges introduced by our dataset, calling for further research. The code
and dataset are publicly available at our project homepage:
https://webcode2m.github.io.
