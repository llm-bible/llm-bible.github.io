---
layout: publication
title: 'Sparrow: Data-efficient Video-llm With Text-to-image Augmentation'
authors: Shukang Yin, Chaoyou Fu, Sirui Zhao, Yunhang Shen, Chunjiang Ge, Yan Yang, Zuwei Long, Yuhan Dai, Yongdong Luo, Haoyu Cao, Tong Xu, Xing Sun, Caifeng Shan, Ran He, Enhong Chen
conference: "Arxiv"
year: 2024
bibkey: yin2024data
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2411.19951'}
  - {name: "Code", url: 'https://github.com/VITA-MLLM/Sparrow'}
tags: ['Has Code', 'Efficiency and Optimization', 'Training Techniques', 'Fine-Tuning', 'Multimodal Models', 'Pretraining Methods']
---
Recent years have witnessed the success of Multimodal Large Language Models
(MLLMs) in the vision understanding domain. The success of these models can
largely be attributed to the dominant scaling law, which states that larger
parameter sizes and data volumes contribute to better performance. Notably,
data scaling has mainly been powered by automatic data pipelines, which center
around the self-instruction of LLMs. The paradigm has been taken for granted
for quite some time, but the study of the effectiveness of scaling with these
data has been neglected for a long time. In this context, this work revisits
scaling with synthetic data and focuses on developing video-LLMs from a
data-centric perspective. Our main study approach is fine-tuning pre-trained
image-LLMs with video data and investigating learning efficiency through data
scaling. Results from our preliminary experiments reveal a low learning
efficiency phenomenon when simply scaling up video data samples, which, through
our probing, can be ascribed to a lack of instruction diversity. Aiming at this
issue, we propose a data augmentation method called Sparrow, which synthesizes
video-like samples from pure text instruction data. Mixing these synthetic
samples with the video data enables a more efficient training scheme. Through
comprehensive experiments, we demonstrate that our proposed method achieves
performance comparable to or even superior to baselines trained with many more
samples. Meanwhile, we find that incorporating these synthetic samples can
boost the performance of long video understanding without training with long
video data. The code and data examples are available at
https://github.com/VITA-MLLM/Sparrow.
