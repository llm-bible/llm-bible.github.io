---
layout: publication
title: "Moextend: Tuning New Experts For Modality And Task Extension"
authors: Zhong Shanshan, Gao Shanghua, Huang Zhongzhan, Wen Wushao, Zitnik Marinka, Zhou Pan
conference: "Arxiv"
year: 2024
bibkey: zhong2024tuning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.03511"}
  - {name: "Code", url: "https://github.com/zhongshsh/MoExtend"}
tags: ['Efficiency And Optimization', 'Fine Tuning', 'Has Code', 'Multimodal Models', 'Pretraining Methods', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
Large language models (LLMs) excel in various tasks but are primarily trained on text data limiting their application scope. Expanding LLM capabilities to include vision-language understanding is vital yet training them on multimodal data from scratch is challenging and costly. Existing instruction tuning methods e.g. LLAVA often connects a pretrained CLIP vision encoder and LLMs via fully fine-tuning LLMs to bridge the modality gap. However full fine-tuning is plagued by catastrophic forgetting i.e. forgetting previous knowledge and high training costs particularly in the era of increasing tasks and modalities. To solve this issue we introduce MoExtend an effective framework designed to streamline the modality adaptation and extension of Mixture-of-Experts (MoE) models. MoExtend seamlessly integrates new experts into pre-trained MoE models endowing them with novel knowledge without the need to tune pretrained models such as MoE and vision encoders. This approach enables rapid adaptation and extension to new modal data or tasks effectively addressing the challenge of accommodating new modalities within LLMs. Furthermore MoExtend avoids tuning pretrained models thus mitigating the risk of catastrophic forgetting. Experimental results demonstrate the efficacy and efficiency of MoExtend in enhancing the multimodal capabilities of LLMs contributing to advancements in multimodal AI research. Code https://github.com/zhongshsh/MoExtend."
