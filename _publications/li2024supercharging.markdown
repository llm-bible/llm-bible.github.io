---
layout: publication
title: 'Llara: Supercharging Robot Learning Data For Vision-language Policy'
authors: Li Xiang, Mata Cristina, Park Jongwoo, Kahatapitiya Kumara, Jang Yoo Sung, Shang Jinghuan, Ranasinghe Kanchana, Burgert Ryan, Cai Mu, Lee Yong Jae, Ryoo Michael S.
conference: "Arxiv"
year: 2024
bibkey: li2024supercharging
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.20095"}
  - {name: "Code", url: "https://github.com/LostXine/LLaRA"}
tags: ['Has Code', 'Multimodal Models', 'Prompting', 'Reinforcement Learning', 'Tools']
---
'Large Language Models (LLMs) equipped with extensive world knowledge and strong reasoning skills can tackle diverse tasks across domains, often by posing them as conversation-style instruction-response pairs. In this paper, we propose LLaRA: Large Language and Robotics Assistant, a framework which formulates robot action policy as conversations, and provides improved responses when trained with auxiliary data that complements policy learning. LLMs with visual inputs, i.e., Vision Language Models (VLMs), have the capacity to process state information as visual-textual prompts and generate optimal policy decisions in text. To train such action policy VLMs, we first introduce an automated pipeline to generate diverse high-quality robotics instruction data from existing behavior cloning data. A VLM finetuned with the resulting collection of datasets based on a conversation-style formulation tailored for robotics tasks, can generate meaningful robot action policy decisions. Our experiments across multiple simulated and real-world environments demonstrate the state-of-the-art performance of the proposed LLaRA framework. The code, datasets, and pretrained models are available at https://github.com/LostXine/LLaRA.'
