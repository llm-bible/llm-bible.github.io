---
layout: publication
title: 'Timesuite: Improving Mllms For Long Video Understanding Via Grounded Tuning'
authors: Xiangyu Zeng, Kunchang Li, Chenting Wang, Xinhao Li, Tianxiang Jiang, Ziang Yan, Songze Li, Yansong Shi, Zhengrong Yue, Yi Wang, Yali Wang, Yu Qiao, Limin Wang
conference: "Arxiv"
year: 2024
bibkey: zeng2024improving
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.19702"}
tags: ['Fine-Tuning', 'Tools', 'Model Architecture', 'Training Techniques', 'Pretraining Methods', 'Multimodal Models']
---
Multimodal Large Language Models (MLLMs) have demonstrated impressive
performance in short video understanding. However, understanding long-form
videos still remains challenging for MLLMs. This paper proposes TimeSuite, a
collection of new designs to adapt the existing short-form video MLLMs for long
video understanding, including a simple yet efficient framework to process long
video sequence, a high-quality video dataset for grounded tuning of MLLMs, and
a carefully-designed instruction tuning task to explicitly incorporate the
grounding supervision in the traditional QA format. Specifically, based on
VideoChat, we propose our long-video MLLM, coined as VideoChat-T, by
implementing a token shuffling to compress long video tokens and introducing
Temporal Adaptive Position Encoding (TAPE) to enhance the temporal awareness of
visual representation. Meanwhile, we introduce the TimePro, a comprehensive
grounding-centric instruction tuning dataset composed of 9 tasks and 349k
high-quality grounded annotations. Notably, we design a new instruction tuning
task type, called Temporal Grounded Caption, to peform detailed video
descriptions with the corresponding time stamps prediction. This explicit
temporal location prediction will guide MLLM to correctly attend on the visual
content when generating description, and thus reduce the hallucination risk
caused by the LLMs. Experimental results demonstrate that our TimeSuite
provides a successful solution to enhance the long video understanding
capability of short-form MLLM, achieving improvement of 5.6% and 6.8% on the
benchmarks of Egoschema and VideoMME, respectively. In addition, VideoChat-T
exhibits robust zero-shot temporal grounding capabilities, significantly
outperforming the existing state-of-the-art MLLMs. After fine-tuning, it
performs on par with the traditional supervised expert models.
