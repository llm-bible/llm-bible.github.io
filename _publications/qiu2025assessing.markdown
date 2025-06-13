---
layout: publication
title: 'Emoagent: Assessing And Safeguarding Human-ai Interaction For Mental Health Safety'
authors: Jiahao Qiu, Yinghui He, Xinzhe Juan, Yimin Wang, Yuhan Liu, Zixin Yao, Yue Wu, Xun Jiang, Ling Yang, Mengdi Wang
conference: "Arxiv"
year: 2025
bibkey: qiu2025assessing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.09689"}
  - {name: "Code", url: "https://github.com/1akaman/EmoAgent"}
tags: ['Responsible AI', 'Agentic', 'Tools', 'Reinforcement Learning', 'Has Code']
---
The rise of LLM-driven AI characters raises safety concerns, particularly for
vulnerable human users with psychological disorders. To address these risks, we
propose EmoAgent, a multi-agent AI framework designed to evaluate and mitigate
mental health hazards in human-AI interactions. EmoAgent comprises two
components: EmoEval simulates virtual users, including those portraying
mentally vulnerable individuals, to assess mental health changes before and
after interactions with AI characters. It uses clinically proven psychological
and psychiatric assessment tools (PHQ-9, PDI, PANSS) to evaluate mental risks
induced by LLM. EmoGuard serves as an intermediary, monitoring users' mental
status, predicting potential harm, and providing corrective feedback to
mitigate risks. Experiments conducted in popular character-based chatbots show
that emotionally engaging dialogues can lead to psychological deterioration in
vulnerable users, with mental state deterioration in more than 34.4% of the
simulations. EmoGuard significantly reduces these deterioration rates,
underscoring its role in ensuring safer AI-human interactions. Our code is
available at: https://github.com/1akaman/EmoAgent
