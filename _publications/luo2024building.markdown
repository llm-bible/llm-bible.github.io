---
layout: publication
title: Duetsim: Building User Simulator With Dual Large Language Models For Task-oriented Dialogues
authors: Luo Xiang, Tang Zhiwen, Wang Jin, Zhang Xuejie
conference: "Arxiv"
year: 2024
bibkey: luo2024building
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.13028"}
  - {name: "Code", url: "https://github.com/suntea233/DuetSim"}
tags: ['Applications', 'Has Code', 'RAG', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
User Simulators play a pivotal role in training and evaluating task-oriented dialogue systems. Traditional user simulators typically rely on human-engineered agendas resulting in generated responses that often lack diversity and spontaneity. Although large language models (LLMs) exhibit a remarkable capacity for generating coherent and contextually appropriate utterances they may fall short when tasked with generating responses that effectively guide users towards their goals particularly in dialogues with intricate constraints and requirements. This paper introduces DuetSim a novel framework designed to address the intricate demands of task-oriented dialogues by leveraging LLMs. DuetSim stands apart from conventional approaches by employing two LLMs in tandem one dedicated to response generation and the other focused on verification. This dual LLM approach empowers DuetSim to produce responses that not only exhibit diversity but also demonstrate accuracy and are preferred by human users. We validate the efficacy of our method through extensive experiments conducted on the MultiWOZ dataset highlighting improvements in response quality and correctness largely attributed to the incorporation of the second LLM. Our code is accessible at https://github.com/suntea233/DuetSim."
