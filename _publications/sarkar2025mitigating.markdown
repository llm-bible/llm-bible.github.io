---
layout: publication
title: 'Mitigating Hallucinations In Vision-language Models Through Image-guided Head Suppression'
authors: Sreetama Sarkar, Yue Che, Alex Gavin, Peter A. Beerel, Souvik Kundu
conference: "Arxiv"
year: 2025
bibkey: sarkar2025mitigating
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.16411'}
  - {name: "Code", url: 'https://github.com/YUECHE77/SPIN'}
tags: ['Attention Mechanism', 'Has Code', 'RAG', 'Applications', 'Model Architecture', 'Multimodal Models']
---
Despite their remarkable progress in multimodal understanding tasks, large vision language models (LVLMs) often suffer from "hallucinations", generating texts misaligned with the visual context. Existing methods aimed at reducing hallucinations through inference time intervention incur a significant increase in latency. To mitigate this, we present SPIN, a task-agnostic attention-guided head suppression strategy that can be seamlessly integrated during inference, without incurring any significant compute or latency overhead. We investigate whether hallucination in LVLMs can be linked to specific model components. Our analysis suggests that hallucinations can be attributed to a dynamic subset of attention heads in each layer. Leveraging this insight, for each text query token, we selectively suppress attention heads that exhibit low attention to image tokens, keeping the top-K attention heads intact. Extensive evaluations on visual question answering and image description tasks demonstrate the efficacy of SPIN in reducing hallucination scores up to 2.7x while maintaining F1, and improving throughput by 1.8x compared to existing alternatives. Code is available at https://github.com/YUECHE77/SPIN.
