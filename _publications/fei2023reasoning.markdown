---
layout: publication
title: Reasoning Implicit Sentiment With Chain45;of45;thought Prompting
authors: Hao Fei, Bobo Li, Qian Liu, Lidong Bing, Fei Li, Tat-seng Chua
conference: "Arxiv"
year: 2023
bibkey: fei2023reasoning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/http://arxiv.org/abs/2305.11255v4"}
  - {name: "Code", url: "https://github.com/scofield7419/THOR&#45;ISA"}
tags: ['GPT', 'Has Code', 'Model Architecture', 'Prompting', 'Tools']
---
While sentiment analysis systems try to determine the sentiment polarities of given targets based on the key opinion expressions in input texts in implicit sentiment analysis (ISA) the opinion cues come in an implicit and obscure manner. Thus detecting implicit sentiment requires the common45;sense and multi45;hop reasoning ability to infer the latent intent of opinion. Inspired by the recent chain45;of45;thought (CoT) idea in this work we introduce a Three45;hop Reasoning (THOR) CoT framework to mimic the human45;like reasoning process for ISA. We design a three45;step prompting principle for THOR to step45;by45;step induce the implicit aspect opinion and finally the sentiment polarity. Our THOR+Flan45;T5 (11B) pushes the state45;of45;the45;art (SoTA) by over 637; F1 on supervised setup. More strikingly THOR+GPT3 (175B) boosts the SoTA by over 5037; F1 on zero45;shot setting. Our code is open at https://github.com/scofield7419/THOR&#45;ISA.
