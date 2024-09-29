---
layout: publication
title: C45;TPT Calibrated Test45;time Prompt Tuning For Vision45;language Models Via Text Feature Dispersion
authors: Yoon Hee Suk, Yoon Eunseop, Tee Joshua Tian Jin, Hasegawa-johnson Mark, Li Yingzhen, Yoo Chang D.
conference: "Arxiv"
year: 2024
bibkey: yoon2024c
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.14119"}
  - {name: "Code", url: "https://github.com/hee&#45;suk&#45;yoon/C&#45;TPT"}
tags: ['Attention Mechanism', 'Fine Tuning', 'Has Code', 'Model Architecture', 'Prompting', 'RAG', 'Reinforcement Learning']
---
In deep learning test45;time adaptation has gained attention as a method for model fine45;tuning without the need for labeled data. A prime exemplification is the recently proposed test45;time prompt tuning for large45;scale vision45;language models such as CLIP. Unfortunately these prompts have been mainly developed to improve accuracy overlooking the importance of calibration which is a crucial aspect for quantifying prediction uncertainty. However traditional calibration methods rely on substantial amounts of labeled data making them impractical for test45;time scenarios. To this end this paper explores calibration during test45;time prompt tuning by leveraging the inherent properties of CLIP. Through a series of observations we find that the prompt choice significantly affects the calibration in CLIP where the prompts leading to higher text feature dispersion result in better45;calibrated predictions. Introducing the Average Text Feature Dispersion (ATFD) we establish its relationship with calibration error and present a novel method Calibrated Test45;time Prompt Tuning (C45;TPT) for optimizing prompts during test45;time with enhanced calibration. Through extensive experiments on different CLIP architectures and datasets we show that C45;TPT can effectively improve the calibration of test45;time prompt tuning without needing labeled data. The code is publicly accessible at https://github.com/hee&#45;suk&#45;yoon/C&#45;TPT.
