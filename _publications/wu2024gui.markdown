---
layout: publication
title: 'GUI Action Narrator: Where And When Did That Action Take Place?'
authors: Qinchen Wu, Difei Gao, Kevin Qinghong Lin, Zhuoyu Wu, Xiangwu Guo, Peiran Li, Weichen Zhang, Hengxu Wang, Mike Zheng Shou
conference: "Arxiv"
year: 2024
bibkey: wu2024gui
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2406.13719'}
tags: ['Attention Mechanism', 'Agentic', 'Efficiency and Optimization', 'Model Architecture', 'Tools', 'Training Techniques', 'Fine-Tuning', 'GPT', 'Prompting', 'Multimodal Models', 'Pretraining Methods']
---
The advent of Multimodal LLMs has significantly enhanced image OCR
recognition capabilities, making GUI automation a viable reality for increasing
efficiency in digital tasks. One fundamental aspect of developing a GUI
automation system is understanding primitive GUI actions. This comprehension is
crucial as it enables agents to learn from user demonstrations, an essential
element of automation. To rigorously evaluate such capabilities, we developed a
video captioning benchmark for GUI actions, comprising 4,189 diverse video
captioning samples. This task presents unique challenges compared to natural
scene video captioning: 1) GUI screenshots typically contain denser information
than natural scenes, and 2) events within GUIs are subtler and occur more
rapidly, requiring precise attention to the appropriate time span and spatial
region for accurate understanding. To address these challenges, we introduce
our GUI action dataset \textbf\{Act2Cap\} as well as a simple yet effective
framework, \textbf\{GUI Narrator\}, for GUI video captioning that utilizes the
cursor as a visual prompt to enhance the interpretation of high-resolution
screenshots. Specifically, a cursor detector is trained on our dataset, and a
multimodal LLM model with mechanisms for selecting keyframes and key regions
generates the captions. Experimental results indicate that even for today's
most advanced multimodal models, such as GPT-4o, the task remains highly
challenging. Additionally, our evaluations show that our strategy effectively
enhances model performance, whether integrated into the fine-tuning of
open-source models or employed as a prompting strategy in closed-source models.
