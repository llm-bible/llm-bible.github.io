---
layout: publication
title: 'Retinalgpt: A Retinal Clinical Preference Conversational Assistant Powered By Large Vision-language Models'
authors: Wenhui Zhu, Xin Li, Xiwen Chen, Peijie Qiu, Vamsi Krishna Vasa, Xuanzhao Dong, Yanxi Chen, Natasha Lepore, Oana Dumitrascu, Yi Su, Yalin Wang
conference: "Arxiv"
year: 2025
bibkey: zhu2025retinal
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.03987"}
  - {name: "Code", url: "https://github.com/Retinal-Research/RetinalGPT"}
tags: ['Multimodal Models', 'Model Architecture', 'Tools', 'RAG', 'GPT', 'Has Code', 'Applications', 'Attention Mechanism']
---
Recently, Multimodal Large Language Models (MLLMs) have gained significant
attention for their remarkable ability to process and analyze non-textual data,
such as images, videos, and audio. Notably, several adaptations of
general-domain MLLMs to the medical field have been explored, including
LLaVA-Med. However, these medical adaptations remain insufficiently advanced in
understanding and interpreting retinal images. In contrast, medical experts
emphasize the importance of quantitative analyses for disease detection and
interpretation. This underscores a gap between general-domain and
medical-domain MLLMs: while general-domain MLLMs excel in broad applications,
they lack the specialized knowledge necessary for precise diagnostic and
interpretative tasks in the medical field. To address these challenges, we
introduce \textit\{RetinalGPT\}, a multimodal conversational assistant for
clinically preferred quantitative analysis of retinal images. Specifically, we
achieve this by compiling a large retinal image dataset, developing a novel
data pipeline, and employing customized visual instruction tuning to enhance
both retinal analysis and enrich medical knowledge. In particular, RetinalGPT
outperforms MLLM in the generic domain by a large margin in the diagnosis of
retinal diseases in 8 benchmark retinal datasets. Beyond disease diagnosis,
RetinalGPT features quantitative analyses and lesion localization, representing
a pioneering step in leveraging LLMs for an interpretable and end-to-end
clinical research framework. The code is available at
https://github.com/Retinal-Research/RetinalGPT
