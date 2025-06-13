---
layout: publication
title: 'Task Preference Optimization: Improving Multimodal Large Language Models With Vision Task Alignment'
authors: Ziang Yan, Zhilin Li, Yinan He, Chenting Wang, Kunchang Li, Xinhao Li, Xiangyu Zeng, Zilei Wang, Yali Wang, Yu Qiao, Limin Wang, Yi Wang
conference: "Arxiv"
year: 2024
bibkey: yan2024task
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.19326"}
  - {name: "Code", url: "https://github.com/OpenGVLab/TPO"}
tags: ['Tools', 'GPT', 'Efficiency and Optimization', 'Applications', 'RAG', 'Training Techniques', 'Has Code', 'Pretraining Methods', 'Multimodal Models']
---
Current multimodal large language models (MLLMs) struggle with fine-grained
or precise understanding of visuals though they give comprehensive perception
and reasoning in a spectrum of vision applications. Recent studies either
develop tool-using or unify specific visual tasks into the autoregressive
framework, often at the expense of overall multimodal performance. To address
this issue and enhance MLLMs with visual tasks in a scalable fashion, we
propose Task Preference Optimization (TPO), a novel method that utilizes
differentiable task preferences derived from typical fine-grained visual tasks.
TPO introduces learnable task tokens that establish connections between
multiple task-specific heads and the MLLM. By leveraging rich visual labels
during training, TPO significantly enhances the MLLM's multimodal capabilities
and task-specific performance. Through multi-task co-training within TPO, we
observe synergistic benefits that elevate individual task performance beyond
what is achievable through single-task training methodologies. Our
instantiation of this approach with VideoChat and LLaVA demonstrates an overall
14.6% improvement in multimodal performance compared to baseline models.
Additionally, MLLM-TPO demonstrates robust zero-shot capabilities across
various tasks, performing comparably to state-of-the-art supervised models. The
code will be released at https://github.com/OpenGVLab/TPO
