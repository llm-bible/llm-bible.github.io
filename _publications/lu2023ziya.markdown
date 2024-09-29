---
layout: publication
title: Ziya-Visual Bilingual Large Vision-Language Model via Multi-Task Instruction Tuning
authors: Lu Junyu, Zhang Dixiang, Wu Xiaojun, Gao Xinyu, Gan Ruyi, Zhang Jiaxing, Song Yan, Zhang Pingjian
conference: "Arxiv"
year: 2023
bibkey: lu2023ziya
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.08166"}
  - {name: "Code", url: "https://huggingface.co/IDEA-CCNL/Ziya-BLIP2-14B-Visual-v1"}
tags: ['Applications', 'Efficiency And Optimization', 'GPT', 'Has Code', 'In Context Learning', 'Language Modeling', 'Model Architecture', 'Multimodal Models', 'Pretraining Methods', 'Prompting', 'Reinforcement Learning', 'Training Techniques', 'Transformer']
---
Recent advancements enlarge the capabilities of large language models (LLMs) in zero-shot image-to-text generation and understanding by integrating multi-modal inputs. However such success is typically limited to English scenarios due to the lack of large-scale and high-quality non-English multi-modal resources making it extremely difficult to establish competitive counterparts in other languages. In this paper we introduce the Ziya-Visual series a set of bilingual large-scale vision-language models (LVLMs) designed to incorporate visual semantics into LLM for multi-modal dialogue. Composed of Ziya-Visual-Base and Ziya-Visual-Chat our models adopt the Querying Transformer from BLIP-2 further exploring the assistance of optimization schemes such as instruction tuning multi-stage training and low-rank adaptation module for visual-language alignment. In addition we stimulate the understanding ability of GPT-4 in multi-modal scenarios translating our gathered English image-text datasets into Chinese and generating instruction-response through the in-context learning method. The experiment results demonstrate that compared to the existing LVLMs Ziya-Visual achieves competitive performance across a wide range of English-only tasks including zero-shot image-text retrieval image captioning and visual question answering. The evaluation leaderboard accessed by GPT-4 also indicates that our models possess satisfactory image-text understanding and generation capabilities in Chinese multi-modal scenario dialogues. Code demo and models are available at ~url https://huggingface.co/IDEA-CCNL/Ziya-BLIP2-14B-Visual-v1.
