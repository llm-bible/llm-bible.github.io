---
layout: publication
title: 'Unveiling Uncertainty: A Deep Dive Into Calibration And Performance Of Multimodal Large Language Models'
authors: Zijun Chen, Wenbo Hu, Guande He, Zhijie Deng, Zheng Zhang, Richang Hong
conference: "Arxiv"
year: 2024
bibkey: chen2024unveiling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.14660"}
  - {name: "Code", url: "https://github.com/hfutml/Calibration-MLLM"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Multimodal Models', 'Pretraining Methods', 'Fine-Tuning', 'Has Code', 'Prompting', 'Applications']
---
Multimodal large language models (MLLMs) combine visual and textual data for
tasks such as image captioning and visual question answering. Proper
uncertainty calibration is crucial, yet challenging, for reliable use in areas
like healthcare and autonomous driving. This paper investigates representative
MLLMs, focusing on their calibration across various scenarios, including before
and after visual fine-tuning, as well as before and after multimodal training
of the base LLMs. We observed miscalibration in their performance, and at the
same time, no significant differences in calibration across these scenarios. We
also highlight how uncertainty differs between text and images and how their
integration affects overall uncertainty. To better understand MLLMs'
miscalibration and their ability to self-assess uncertainty, we construct the
IDK (I don't know) dataset, which is key to evaluating how they handle
unknowns. Our findings reveal that MLLMs tend to give answers rather than admit
uncertainty, but this self-assessment improves with proper prompt adjustments.
Finally, to calibrate MLLMs and enhance model reliability, we propose
techniques such as temperature scaling and iterative prompt optimization. Our
results provide insights into improving MLLMs for effective and responsible
deployment in multimodal applications. Code and IDK dataset:
https://github.com/hfutml/Calibration-MLLM.
