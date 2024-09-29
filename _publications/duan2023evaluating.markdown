---
layout: publication
title: Botchat Evaluating Llms Capabilities Of Having Multi45;turn Dialogues
authors: Duan Haodong, Wei Jueqi, Wang Chonghua, Liu Hongwei, Fang Yixiao, Zhang Songyang, Lin Dahua, Chen Kai
conference: "Arxiv"
year: 2023
bibkey: duan2023evaluating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.13650"}
  - {name: "Code", url: "https://github.com/open&#45;compass/BotChat/"}
tags: ['GPT', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Reinforcement Learning']
---
Interacting with human via high45;quality multi45;turn dialogues is a key feature of large language models (LLMs). However human45;based evaluation of such capability involves intensive manual labor. This report provides a preliminary evaluation of existing large language models for human45;style multi45;turn chatting through an LLM45;based approach. We start from real45;world human dialogues and keep the very first utterances as the ChatSEED. Then we prompt LLMs to generate a full multi45;turn dialogue (tens of utterances) based on the ChatSEED utterance by utterance. Finally we adopt state45;of45;the45;art LLMs (GPT45;4 etc) as the judge to evaluate the generated dialogues. With different evaluation protocols we come to substantially identical conclusions. We find that GPT45;4 can generate human45;style multi45;turn dialogues with impressive quality significantly outperforms its counterparts. Its difficult for a discriminator to distinguish between GPT45;4 generated dialogues and human dialogues. In contrast other LLMs struggle to generate multi45;turn dialogues of satisfactory quality due to poor instruction45;following capability tendency to generate lengthy utterances or limited general capability. All data and codes will be provided in https://github.com/open&#45;compass/BotChat/ and we hope they can serve as a valuable resource for evaluating multi45;turn chatting capabilities of LLMs.
