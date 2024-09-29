---
layout: publication
title: When Hindsight Is Not 20/20 Testing Limits On Reflective Thinking In Large Language Models
authors: Li Yanhong, Yang Chenghao, Ettinger Allyson
conference: "Arxiv"
year: 2024
bibkey: li2024when
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.09129"}
  - {name: "Code", url: "https://github.com/yanhong&#45;lbh/LLM&#45;SelfReflection&#45;Eval"}
tags: ['Has Code', 'Pretraining Methods', 'Prompting']
---
Recent studies suggest that self45;reflective prompting can significantly enhance the reasoning capabilities of Large Language Models (LLMs). However the use of external feedback as a stop criterion raises doubts about the true extent of LLMs ability to emulate human45;like self45;reflection. In this paper we set out to clarify these capabilities under a more stringent evaluation setting in which we disallow any kind of external feedback. Our findings under this setting show a split while self45;reflection enhances performance in TruthfulQA it adversely affects results in HotpotQA. We conduct follow45;up analyses to clarify the contributing factors in these patterns and find that the influence of self45;reflection is impacted both by reliability of accuracy in models initial responses and by overall question difficulty specifically self45;reflection shows the most benefit when models are less likely to be correct initially and when overall question difficulty is higher. We also find that self45;reflection reduces tendency toward majority voting. Based on our findings we propose guidelines for decisions on when to implement self45;reflection. We release the codebase for reproducing our experiments at https://github.com/yanhong&#45;lbh/LLM&#45;SelfReflection&#45;Eval.
