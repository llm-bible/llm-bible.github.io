---
layout: publication
title: 'Align Anything: Training All-modality Models To Follow Instructions With Language Feedback'
authors: Jiaming Ji, Jiayi Zhou, Hantao Lou, Boyuan Chen, Donghai Hong, Xuyao Wang, Wenqi Chen, Kaile Wang, Rui Pan, Jiahao Li, Mohan Wang, Josef Dai, Tianyi Qiu, Hua Xu, Dong Li, Weipeng Chen, Jun Song, Bo Zheng, Yaodong Yang
conference: "Arxiv"
year: 2024
bibkey: ji2024align
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2412.15838'}
  - {name: "Code", url: 'https://github.com/PKU-Alignment/align-anything'}
tags: ['Agentic', 'Has Code', 'Training Techniques', 'Tools', 'Multimodal Models', 'Reinforcement Learning']
---
Reinforcement learning from human feedback (RLHF) has proven effective in
enhancing the instruction-following capabilities of large language models;
however, it remains underexplored in the cross-modality domain. As the number
of modalities increases, aligning all-modality models with human intentions --
such as instruction following -- becomes a pressing challenge. In this work, we
make the first attempt to fine-tune all-modality models (i.e. input and output
with any modality, also named any-to-any models) using human preference data
across all modalities (including text, image, audio, and video), ensuring its
behavior aligns with human intentions. This endeavor presents several
challenges. First, there is no large-scale all-modality human preference data
in existing open-source resources, as most datasets are limited to specific
modalities, predominantly text and image. Secondly, the effectiveness of binary
preferences in RLHF for post-training alignment in complex all-modality
scenarios remains an unexplored area. Finally, there is a lack of a systematic
framework to evaluate the capabilities of all-modality models, particularly
regarding modality selection and synergy. To address these challenges, we
propose the align-anything framework, which includes meticulously annotated
200k all-modality human preference data. Then, we introduce an alignment method
that learns from unified language feedback, effectively capturing complex
modality-specific human preferences and enhancing the model's
instruction-following capabilities. Furthermore, to assess performance
improvements in all-modality models after post-training alignment, we construct
a challenging all-modality capability evaluation framework -- eval-anything.
All data, models, and code frameworks have been open-sourced for the community.
For more details, please refer to
https://github.com/PKU-Alignment/align-anything.
