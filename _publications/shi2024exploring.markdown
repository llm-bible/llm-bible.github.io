---
layout: publication
title: 'Eagle: Exploring The Design Space For Multimodal Llms With Mixture Of Encoders'
authors: Shi Min, Liu Fuxiao, Wang Shihao, Liao Shijia, Radhakrishnan Subhashree, Huang De-an, Yin Hongxu, Sapra Karan, Yacoob Yaser, Shi Humphrey, Catanzaro Bryan, Tao Andrew, Kautz Jan, Yu Zhiding, Liu Guilin
conference: "Arxiv"
year: 2024
bibkey: shi2024exploring
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.15998"}
  - {name: "Code", url: "https://github.com/NVlabs/Eagle"}
tags: ['Fine Tuning', 'Has Code', 'Model Architecture', 'Multimodal Models', 'Reinforcement Learning']
---
The ability to accurately interpret complex visual information is a crucial topic of multimodal large language models (MLLMs). Recent work indicates that enhanced visual perception significantly reduces hallucinations and improves performance on resolution-sensitive tasks, such as optical character recognition and document analysis. A number of recent MLLMs achieve this goal using a mixture of vision encoders. Despite their success, there is a lack of systematic comparisons and detailed ablation studies addressing critical aspects, such as expert selection and the integration of multiple vision experts. This study provides an extensive exploration of the design space for MLLMs using a mixture of vision encoders and resolutions. Our findings reveal several underlying principles common to various existing strategies, leading to a streamlined yet effective design approach. We discover that simply concatenating visual tokens from a set of complementary vision encoders is as effective as more complex mixing architectures or strategies. We additionally introduce Pre-Alignment to bridge the gap between vision-focused encoders and language tokens, enhancing model coherence. The resulting family of MLLMs, Eagle, surpasses other leading open-source models on major MLLM benchmarks. Models and code: https://github.com/NVlabs/Eagle
