---
layout: publication
title: 'Safe Unlearning: A Surprisingly Effective And Generalizable Solution To Defend Against Jailbreak Attacks'
authors: Zhang Zhexin, Yang Junxiao, Ke Pei, Cui Shiyao, Zheng Chujie, Wang Hongning, Huang Minlie
conference: "Arxiv"
year: 2024
bibkey: zhang2024safe
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.02855"}
  - {name: "Code", url: "https://github.com/thu-coai/SafeUnlearning"}
tags: ['Fine Tuning', 'Has Code', 'Pretraining Methods', 'Prompting', 'Reinforcement Learning', 'Responsible AI', 'Security', 'Training Techniques']
---
LLMs are known to be vulnerable to jailbreak attacks even after safety alignment. An important observation is that while different types of jailbreak attacks can generate significantly different queries they mostly result in similar responses that are rooted in the same harmful knowledge (e.g. detailed steps to make a bomb). Therefore we conjecture that directly unlearn the harmful knowledge in the LLM can be a more effective way to defend against jailbreak attacks than the mainstream supervised fine-tuning (SFT) based approaches. Our extensive experiments confirmed our insight and suggested surprising generalizability of our unlearning-based approach using only 20 raw harmful questions (emphwithout) any jailbreak prompt during training our solution reduced the Attack Success Rate (ASR) in Vicuna-7B on (emphout-of-distribution) (OOD) harmful questions wrapped with various complex jailbreak prompts from 82.637; to 7.737;. This significantly outperforms Llama2-7B-Chat which is fine-tuned on about 0.1M safety alignment samples but still has an ASR of 21.937; even under the help of an additional safety system prompt. Further analysis reveals that the generalization ability of our solution stems from the intrinsic relatedness among harmful responses across harmful questions (e.g. response patterns shared steps and actions and similarity among their learned representations in the LLM). Our code is available at (urlhttps://github.com/thu-coai/SafeUnlearning\}\)."
