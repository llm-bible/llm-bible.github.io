---
layout: publication
title: Botchat: Evaluating Llms' Capabilities Of Having Multi-turn Dialogues
authors: Duan Haodong, Wei Jueqi, Wang Chonghua, Liu Hongwei, Fang Yixiao, Zhang Songyang, Lin Dahua, Chen Kai
conference: "Arxiv"
year: 2023
bibkey: duan2023evaluating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.13650"}
  - {name: "Code", url: "https://github.com/open-compass/BotChat/"}
tags: ['GPT', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Reinforcement Learning']
---
Interacting with human via high-quality multi-turn dialogues is a key feature of large language models (LLMs). However human-based evaluation of such capability involves intensive manual labor. This report provides a preliminary evaluation of existing large language models for human-style multi-turn chatting through an LLM-based approach. We start from real-world human dialogues and keep the very first utterances as the ChatSEED. Then we prompt LLMs to generate a full multi-turn dialogue (tens of utterances) based on the ChatSEED utterance by utterance. Finally we adopt state-of-the-art LLMs (GPT-4 (etc)) as the judge to evaluate the generated dialogues. With different evaluation protocols we come to substantially identical conclusions. We find that GPT-4 can generate human-style multi-turn dialogues with impressive quality significantly outperforms its counterparts. Its difficult for a discriminator to distinguish between GPT-4 generated dialogues and human dialogues. In contrast other LLMs struggle to generate multi-turn dialogues of satisfactory quality due to poor instruction-following capability tendency to generate lengthy utterances or limited general capability. All data and codes will be provided in https://github.com/open-compass/BotChat/ and we hope they can serve as a valuable resource for evaluating multi-turn chatting capabilities of LLMs.
