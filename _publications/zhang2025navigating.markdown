---
layout: publication
title: 'Agentalign: Navigating Safety Alignment In The Shift From Informative To Agentic Large Language Models'
authors: Jinchuan Zhang, Lu Yin, Yan Zhou, Songlin Hu
conference: "Arxiv"
year: 2025
bibkey: zhang2025navigating
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.23020'}
tags: ['Agentic', 'RAG', 'Security', 'Training Techniques', 'Tools', 'Fine-Tuning', 'Prompting', 'Responsible AI', 'Pretraining Methods']
---
The acquisition of agentic capabilities has transformed LLMs from "knowledge providers" to "action executors", a trend that while expanding LLMs' capability boundaries, significantly increases their susceptibility to malicious use. Previous work has shown that current LLM-based agents execute numerous malicious tasks even without being attacked, indicating a deficiency in agentic use safety alignment during the post-training phase. To address this gap, we propose AgentAlign, a novel framework that leverages abstract behavior chains as a medium for safety alignment data synthesis. By instantiating these behavior chains in simulated environments with diverse tool instances, our framework enables the generation of highly authentic and executable instructions while capturing complex multi-step dynamics. The framework further ensures model utility by proportionally synthesizing benign instructions through non-malicious interpretations of behavior chains, precisely calibrating the boundary between helpfulness and harmlessness. Evaluation results on AgentHarm demonstrate that fine-tuning three families of open-source models using our method substantially improves their safety (35.8% to 79.5% improvement) while minimally impacting or even positively enhancing their helpfulness, outperforming various prompting methods. The dataset and code have both been open-sourced.
