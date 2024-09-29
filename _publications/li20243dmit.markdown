---
layout: publication
title: 3DMIT 3D Multi-modal Instruction Tuning For Scene Understanding
authors: Li Zeju, Zhang Chao, Wang Xiaoyan, Ren Ruilong, Xu Yifan, Ma Ruifei, Liu Xiangde
conference: "Arxiv"
year: 2024
bibkey: li20243dmit
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.03201"}
  - {name: "Code", url: "https://github.com/staymylove/3DMIT"}
tags: ['Has Code', 'Multimodal Models', 'Prompting', 'Reinforcement Learning']
---
The remarkable potential of multi-modal large language models (MLLMs) in comprehending both vision and language information has been widely acknowledged. However the scarcity of 3D scenes-language pairs in comparison to their 2D counterparts coupled with the inadequacy of existing approaches in understanding of 3D scenes by LLMs poses a significant challenge. In response we collect and construct an extensive dataset comprising 75K instruction-response pairs tailored for 3D scenes. This dataset addresses tasks related to 3D VQA 3D grounding and 3D conversation. To further enhance the integration of 3D spatial information into LLMs we introduce a novel and efficient prompt tuning paradigm 3DMIT. This paradigm eliminates the alignment stage between 3D scenes and language and extends the instruction prompt with the 3D modality information including the entire scene and segmented objects. We evaluate the effectiveness of our method across diverse tasks in the 3D scene domain and find that our approach serves as a strategic means to enrich LLMs comprehension of the 3D world. Our code is available at https://github.com/staymylove/3DMIT.
