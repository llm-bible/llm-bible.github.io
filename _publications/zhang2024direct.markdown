---
layout: publication
title: 'Direct Preference Optimization Of Video Large Multimodal Models From Language Model Reward'
authors: Ruohong Zhang, Liangke Gui, Zhiqing Sun, Yihao Feng, Keyang Xu, Yuanhan Zhang, Di Fu, Chunyuan Li, Alexander Hauptmann, Yonatan Bisk, Yiming Yang
conference: "Arxiv"
year: 2024
bibkey: zhang2024direct
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.01258"}
tags: ['Tools', 'GPT', 'Efficiency and Optimization', 'Model Architecture', 'Reinforcement Learning', 'Multimodal Models']
---
Preference modeling techniques, such as direct preference optimization (DPO),
has shown effective in enhancing the generalization abilities of large language
model (LLM). However, in tasks involving video instruction-following, providing
informative feedback, especially for detecting hallucinations in generated
responses, remains a significant challenge. Previous studies have explored
using large large multimodal models (LMMs) as reward models to guide preference
modeling, but their ability to accurately assess the factuality of generated
responses compared to corresponding videos has not been conclusively
established. This paper introduces a novel framework that utilizes detailed
video captions as a proxy of video content, enabling language models to
incorporate this information as supporting evidence for scoring video Question
Answering (QA) predictions. Our approach demonstrates robust alignment with
OpenAI GPT-4V model's reward mechanism, which directly takes video frames as
input. Furthermore, we show that applying this tailored reward through DPO
significantly improves the performance of video LMMs on video QA tasks.
