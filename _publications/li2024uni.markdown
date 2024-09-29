---
layout: publication
title: Uni45;moe Scaling Unified Multimodal Llms With Mixture Of Experts
authors: Li Yunxin, Jiang Shenyuan, Hu Baotian, Wang Longyue, Zhong Wanqi, Luo Wenhan, Ma Lin, Zhang Min
conference: "Arxiv"
year: 2024
bibkey: li2024uni
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.11273"}
  - {name: "Code", url: "https://github.com/HITsz&#45;TMG/UMOE&#45;Scaling&#45;Unified&#45;Multimodal&#45;LLMs"}
tags: ['Ethics And Bias', 'Fine Tuning', 'Has Code', 'Model Architecture', 'Multimodal Models', 'Tools', 'Training Techniques']
---
Recent advancements in Multimodal Large Language Models (MLLMs) underscore the significance of scalable models and data to boost performance yet this often incurs substantial computational costs. Although the Mixture of Experts (MoE) architecture has been employed to efficiently scale large language and image45;text models these efforts typically involve fewer experts and limited modalities. To address this our work presents the pioneering attempt to develop a unified MLLM with the MoE architecture named Uni45;MoE that can handle a wide array of modalities. Specifically it features modality45;specific encoders with connectors for a unified multimodal representation. We also implement a sparse MoE architecture within the LLMs to enable efficient training and inference through modality45;level data parallelism and expert45;level model parallelism. To enhance the multi45;expert collaboration and generalization we present a progressive training strategy 1) Cross45;modality alignment using various connectors with different cross45;modality data 2) Training modality45;specific experts with cross45;modality instruction data to activate experts preferences and 3) Tuning the Uni45;MoE framework utilizing Low45;Rank Adaptation (LoRA) on mixed multimodal instruction data. We evaluate the instruction45;tuned Uni45;MoE on a comprehensive set of multimodal datasets. The extensive experimental results demonstrate Uni45;MoEs principal advantage of significantly reducing performance bias in handling mixed multimodal datasets alongside improved multi45;expert collaboration and generalization. Our findings highlight the substantial potential of MoE frameworks in advancing MLLMs and the code is available at https://github.com/HITsz&#45;TMG/UMOE&#45;Scaling&#45;Unified&#45;Multimodal&#45;LLMs.
