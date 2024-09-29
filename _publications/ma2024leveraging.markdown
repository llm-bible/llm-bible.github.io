---
layout: publication
title: Eventlens Leveraging Event45;aware Pretraining And Cross45;modal Linking Enhances Visual Commonsense Reasoning
authors: Ma Mingjie, Yu Zhihuan, Ma Yichao, Li Guohui
conference: "Arxiv"
year: 2024
bibkey: ma2024leveraging
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.13847"}
tags: ['Multimodal Models', 'Pretraining Methods', 'Prompting', 'RAG', 'Training Techniques']
---
Visual Commonsense Reasoning (VCR) is a cognitive task challenging models to answer visual questions requiring human commonsense and to provide rationales explaining why the answers are correct. With emergence of Large Language Models (LLMs) it is natural and imperative to explore their applicability to VCR. However VCR task demands more external knowledge to tackle its challenging questions necessitating special designs to activate LLMs commonsense reasoning abilities. Also most existing Multimodal LLMs adopted an abstraction of entire input image which makes it difficult to comprehend VCRs unique co45;reference tags between image regions and text posing challenges for fine45;grained alignment. To address these issues we propose EventLens that leverages Event45;Aware Pretraining and Cross45;modal Linking and EnhanceS VCR. First by emulating the cognitive process of human reasoning an Event45;Aware Pretraining auxiliary task is introduced to better activate LLMs global comprehension of intricate scenarios. Second during fine45;tuning we further utilize reference tags to bridge RoI features with texts while preserving both modality semantics. Finally we use instruct45;style prompts to narrow the gap between pretraining and fine45;tuning and task45;specific adapters to better integrate LLMs inherent knowledge with new commonsense. Experimental results show the effectiveness of our proposed auxiliary task and fine45;grained linking strategy.
