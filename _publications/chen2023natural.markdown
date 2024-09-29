---
layout: publication
title: Natural Response Generation For Chinese Reading Comprehension
authors: Chen Nuo, Li Hongguang, Bao Yinan, Wang Baoyuan, Li Jia
conference: "EMNLP"
year: 2023
bibkey: chen2023natural
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2302.08817"}
tags: ['Agentic', 'Applications', 'Attention Mechanism', 'Model Architecture', 'Prompting', 'Tools', 'Training Techniques']
---
Machine reading comprehension (MRC) is an important area of conversation agents and draws a lot of attention. However there is a notable limitation to current MRC benchmarks The labeled answers are mostly either spans extracted from the target corpus or the choices of the given candidates ignoring the natural aspect of high45;quality responses. As a result MRC models trained on these datasets can not generate human45;like responses in real QA scenarios. To this end we construct a new dataset called Penguin to promote the research of MRC providing a training and test bed for natural response generation to real scenarios. Concretely Penguin consists of 200k training data with high45;quality fluent and well45;informed responses. Penguin is the first benchmark towards natural response generation in Chinese MRC on a relatively large scale. To address the challenges in Penguin we develop two strong baselines end45;to45;end and two45;stage frameworks. Following that we further design Prompt45;BART fine45;tuning the pre45;trained generative language models with a mixture of prefix prompts in Penguin. Extensive experiments validated the effectiveness of this design.
