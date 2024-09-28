---
layout: publication
title: JoTR A Joint Transformer and Reinforcement Learning Framework for Dialog Policy Learning
authors: Kwan Wai-chung, Wang Huimin, Wang Hongru, Wang Zezhong, Wu Xian, Zheng Yefeng, Wong Kam-fai
conference: "Arxiv"
year: 2023
bibkey: kwan2023jotr
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.00230"}
tags: ['ARXIV', 'Model Architecture', 'Tools', 'Transformer']
---
Dialogue policy learning (DPL) is a crucial component of dialogue modelling. Its primary role is to determine the appropriate abstract response commonly referred to as the dialogue action. Traditional DPL methodologies have treated this as a sequential decision problem using pre-defined action candidates extracted from a corpus. However these incomplete candidates can significantly limit the diversity of responses and pose challenges when dealing with edge cases which are scenarios that occur only at extreme operating parameters. To address these limitations we introduce a novel framework JoTR. This framework is unique as it leverages a text-to-text Transformer-based model to generate flexible dialogue actions. Unlike traditional methods JoTR formulates a word-level policy that allows for a more dynamic and adaptable dialogue action generation without the need for any action templates. This setting enhances the diversity of responses and improves the systems ability to handle edge cases effectively. In addition JoTR employs reinforcement learning with a reward-shaping mechanism to efficiently finetune the word-level dialogue policy which allows the model to learn from its interactions improving its performance over time. We conducted an extensive evaluation of JoTR to assess its effectiveness. Our extensive evaluation shows that JoTR achieves state-of-the-art performance on two benchmark dialogue modelling tasks as assessed by both user simulators and human evaluators.
