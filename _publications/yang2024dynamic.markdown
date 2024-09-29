---
layout: publication
title: DGL Dynamic Global-local Prompt Tuning For Text-video Retrieval
authors: Yang Xiangpeng, Zhu Linchao, Wang Xiaohan, Yang Yi
conference: "Arxiv"
year: 2024
bibkey: yang2024dynamic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.10588"}
  - {name: "Code", url: "https://github.com/knightyxp/DGL"}
tags: ['Attention Mechanism', 'Has Code', 'Model Architecture', 'Multimodal Models', 'Prompting', 'RAG', 'Transformer']
---
Text-video retrieval is a critical multi-modal task to find the most relevant video for a text query. Although pretrained models like CLIP have demonstrated impressive potential in this area the rising cost of fully finetuning these models due to increasing model size continues to pose a problem. To address this challenge prompt tuning has emerged as an alternative. However existing works still face two problems when adapting pretrained image-text models to downstream video-text tasks (1) The visual encoder could only encode frame-level features and failed to extract global-level general video information. (2) Equipping the visual and text encoder with separated prompts failed to mitigate the visual-text modality gap. To this end we propose DGL a cross-modal Dynamic prompt tuning method with Global-Local video attention. In contrast to previous prompt tuning methods we employ the shared latent space to generate local-level text and frame prompts that encourage inter-modal interaction. Furthermore we propose modeling video in a global-local attention mechanism to capture global video information from the perspective of prompt tuning. Extensive experiments reveal that when only 0.6737; parameters are tuned our cross-modal prompt tuning strategy DGL outperforms or is comparable to fully finetuning methods on MSR-VTT VATEX LSMDC and ActivityNet datasets. Code will be available at https://github.com/knightyxp/DGL"
