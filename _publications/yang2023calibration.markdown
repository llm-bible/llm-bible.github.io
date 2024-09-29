---
layout: publication
title: On The Calibration Of Multilingual Question Answering Llms
authors: Yang Yahan, Dan Soham, Roth Dan, Lee Insup
conference: "Arxiv"
year: 2023
bibkey: yang2023calibration
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.08669"}
tags: ['Applications', 'Reinforcement Learning']
---
Multilingual pre45;trained Large Language Models (LLMs) are incredibly effective at Question Answering (QA) a core task in Natural Language Understanding achieving high accuracies on several multilingual benchmarks. However little is known about how well their confidences are calibrated. In this paper we comprehensively benchmark the calibration of several multilingual LLMs (MLLMs) on a variety of QA tasks. We perform extensive experiments spanning encoder45;only encoder45;decoder and decoder45;only QA models (size varying from 110M to 7B parameters) and diverse languages including both high45; and low45;resource ones. We study different dimensions of calibration in in45;distribution out45;of45;distribution and cross45;lingual transfer settings and investigate strategies to improve it including post45;hoc methods and regularized fine45;tuning. For decoder45;only LLMs such as LlaMa2 we additionally find that in45;context learning improves confidence calibration on multilingual data. We also conduct several ablation experiments to study the effect of language distances language corpus size and model size on calibration and how multilingual models compare with their monolingual counterparts for diverse tasks and languages. Our experiments suggest that the multilingual QA models are poorly calibrated for languages other than English and incorporating a small set of cheaply translated multilingual samples during fine45;tuning/calibration effectively enhances the calibration performance.
