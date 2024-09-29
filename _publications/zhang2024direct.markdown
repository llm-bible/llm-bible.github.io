---
layout: publication
title: Direct Preference Optimization Of Video Large Multimodal Models From Language Model Reward
authors: Zhang Ruohong, Gui Liangke, Sun Zhiqing, Feng Yihao, Xu Keyang, Zhang Yuanhan, Fu Di, Li Chunyuan, Hauptmann Alexander, Bisk Yonatan, Yang Yiming
conference: "Arxiv"
year: 2024
bibkey: zhang2024direct
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.01258"}
tags: ['Applications', 'Efficiency And Optimization', 'GPT', 'Model Architecture', 'Multimodal Models', 'Reinforcement Learning', 'Tools']
---
Preference modeling techniques such as direct preference optimization (DPO) has shown effective in enhancing the generalization abilities of large language model (LLM). However in tasks involving video instruction45;following providing informative feedback especially for detecting hallucinations in generated responses remains a significant challenge. Previous studies have explored using large large multimodal models (LMMs) as reward models to guide preference modeling but their ability to accurately assess the factuality of generated responses compared to corresponding videos has not been conclusively established. This paper introduces a novel framework that utilizes detailed video captions as a proxy of video content enabling language models to incorporate this information as supporting evidence for scoring video Question Answering (QA) predictions. Our approach demonstrates robust alignment with OpenAI GPT45;4V models reward mechanism which directly takes video frames as input. Furthermore we show that applying this tailored reward through DPO significantly improves the performance of video LMMs on video QA tasks.
