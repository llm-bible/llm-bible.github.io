---
layout: publication
title: DGL Dynamic Global45;local Prompt Tuning For Text45;video Retrieval
authors: Yang Xiangpeng, Zhu Linchao, Wang Xiaohan, Yang Yi
conference: "Arxiv"
year: 2024
bibkey: yang2024dynamic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.10588"}
  - {name: "Code", url: "https://github.com/knightyxp/DGL"}
tags: ['Attention Mechanism', 'Has Code', 'Model Architecture', 'Prompting', 'RAG', 'Transformer']
---
Text45;video retrieval is a critical multi45;modal task to find the most relevant video for a text query. Although pretrained models like CLIP have demonstrated impressive potential in this area the rising cost of fully finetuning these models due to increasing model size continues to pose a problem. To address this challenge prompt tuning has emerged as an alternative. However existing works still face two problems when adapting pretrained image45;text models to downstream video45;text tasks (1) The visual encoder could only encode frame45;level features and failed to extract global45;level general video information. (2) Equipping the visual and text encoder with separated prompts failed to mitigate the visual45;text modality gap. To this end we propose DGL a cross45;modal Dynamic prompt tuning method with Global45;Local video attention. In contrast to previous prompt tuning methods we employ the shared latent space to generate local45;level text and frame prompts that encourage inter45;modal interaction. Furthermore we propose modeling video in a global45;local attention mechanism to capture global video information from the perspective of prompt tuning. Extensive experiments reveal that when only 0.6737; parameters are tuned our cross45;modal prompt tuning strategy DGL outperforms or is comparable to fully finetuning methods on MSR45;VTT VATEX LSMDC and ActivityNet datasets. Code will be available at https://github.com/knightyxp/DGL
