---
layout: publication
title: Llms Meet Long Video Advancing Long Video Question Answering With An Interactive Visual Adapter In Llms
authors: Li Yunxin, Chen Xinyu, Hu Baotain, Zhang Min
conference: "Arxiv"
year: 2024
bibkey: li2024llms
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.13546"}
tags: ['Applications', 'Merging', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Transformer']
---
Long video understanding is a significant and ongoing challenge in the intersection of multimedia and artificial intelligence. Employing large language models (LLMs) for comprehending video becomes an emerging and promising method. However this approach incurs high computational costs due to the extensive array of video tokens experiences reduced visual clarity as a consequence of token aggregation and confronts challenges arising from irrelevant visual tokens while answering video-related questions. To alleviate these issues we present an Interactive Visual Adapter (IVA) within LLMs designed to enhance interaction with fine-grained visual elements. Specifically we first transform long videos into temporal video tokens via leveraging a visual encoder alongside a pretrained causal transformer then feed them into LLMs with the video instructions. Subsequently we integrated IVA which contains a lightweight temporal frame selector and a spatial feature interactor within the internal blocks of LLMs to capture instruction-aware and fine-grained visual signals. Consequently the proposed video-LLM facilitates a comprehensive understanding of long video content through appropriate long video modeling and precise visual interactions. We conducted extensive experiments on nine video understanding benchmarks and experimental results show that our interactive visual adapter significantly improves the performance of video LLMs on long video QA tasks. Ablation studies further verify the effectiveness of IVA in understanding long and short video.
