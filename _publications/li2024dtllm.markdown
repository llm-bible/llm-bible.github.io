---
layout: publication
title: 'DTLLM-VLT: Diverse Text Generation For Visual Language Tracking Based On LLM'
authors: Xuchen Li, Xiaokun Feng, Shiyu Hu, Meiqi Wu, Dailing Zhang, Jing Zhang, Kaiqi Huang
conference: "Arxiv"
year: 2024
bibkey: li2024dtllm
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.12139"}
tags: ['Tools', 'Applications', 'RAG', 'Language Modeling', 'Reinforcement Learning', 'Prompting']
---
Visual Language Tracking (VLT) enhances single object tracking (SOT) by
integrating natural language descriptions from a video, for the precise
tracking of a specified object. By leveraging high-level semantic information,
VLT guides object tracking, alleviating the constraints associated with relying
on a visual modality. Nevertheless, most VLT benchmarks are annotated in a
single granularity and lack a coherent semantic framework to provide scientific
guidance. Moreover, coordinating human annotators for high-quality annotations
is laborious and time-consuming. To address these challenges, we introduce
DTLLM-VLT, which automatically generates extensive and multi-granularity text
to enhance environmental diversity. (1) DTLLM-VLT generates scientific and
multi-granularity text descriptions using a cohesive prompt framework. Its
succinct and highly adaptable design allows seamless integration into various
visual tracking benchmarks. (2) We select three prominent benchmarks to deploy
our approach: short-term tracking, long-term tracking, and global instance
tracking. We offer four granularity combinations for these benchmarks,
considering the extent and density of semantic information, thereby showcasing
the practicality and versatility of DTLLM-VLT. (3) We conduct comparative
experiments on VLT benchmarks with different text granularities, evaluating and
analyzing the impact of diverse text on tracking performance. Conclusionally,
this work leverages LLM to provide multi-granularity semantic information for
VLT task from efficient and diverse perspectives, enabling fine-grained
evaluation of multi-modal trackers. In the future, we believe this work can be
extended to more datasets to support vision datasets understanding.
