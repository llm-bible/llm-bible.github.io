---
layout: publication
title: Bt45;adapter Video Conversation Is Feasible Without Video Instruction Tuning
authors: Liu Ruyang, Li Chen, Ge Yixiao, Shan Ying, Li Thomas H., Li Ge
conference: "Arxiv"
year: 2023
bibkey: liu2023bt
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.15785"}
tags: ['Agentic', 'Fine Tuning', 'Masked Language Model', 'Multimodal Models', 'Training Techniques']
---
The recent progress in Large Language Models (LLM) has spurred various advancements in image45;language conversation agents while how to build a proficient video45;based dialogue system is still under exploration. Considering the extensive scale of LLM and visual backbone minimal GPU memory is left for facilitating effective temporal modeling which is crucial for comprehending and providing feedback on videos. To this end we propose Branching Temporal Adapter (BT45;Adapter) a novel method for extending image45;language pretrained models into the video domain. Specifically BT45;Adapter serves as a plug45;and45;use temporal modeling branch alongside the pretrained visual encoder which is tuned while keeping the backbone frozen. Just pretrained once BT45;Adapter can be seamlessly integrated into all image conversation models using this version of CLIP enabling video conversations without the need for video instructions. Besides we develop a unique asymmetric token masking strategy inside the branch with tailor45;made training tasks for BT45;Adapter facilitating faster convergence and better results. Thanks to BT45;Adapter we are able to empower existing multimodal dialogue models with strong video understanding capabilities without incurring excessive GPU costs. Without bells and whistles BT45;Adapter achieves (1) state45;of45;the45;art zero45;shot results on various video tasks using thousands of fewer GPU hours. (2) better performance than current video chatbots without any video instruction tuning. (3) state45;of45;the45;art results of video chatting using video instruction tuning outperforming previous SOTAs by a large margin.
