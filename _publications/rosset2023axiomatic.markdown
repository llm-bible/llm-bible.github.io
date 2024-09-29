---
layout: publication
title: Axiomatic Preference Modeling For Longform Question Answering
authors: Rosset Corby, Zheng Guoqing, Dibia Victor, Awadallah Ahmed, Bennett Paul
conference: "Arxiv"
year: 2023
bibkey: rosset2023axiomatic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.02206"}
  - {name: "Code", url: "https://huggingface.co/corbyrosset/axiomatic&#95;preference&#95;model"}
tags: ['Agentic', 'Applications', 'GPT', 'Has Code', 'Model Architecture', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
The remarkable abilities of large language models (LLMs) like GPT45;4 partially stem from post45;training processes like Reinforcement Learning from Human Feedback (RLHF) involving human preferences encoded in a reward model. However these reward models (RMs) often lack direct knowledge of why or under what principles the preferences annotations were made. In this study we identify principles that guide RMs to better align with human preferences and then develop an axiomatic framework to generate a rich variety of preference signals to uphold them. We use these axiomatic signals to train a model for scoring answers to longform questions. Our approach yields a Preference Model with only about 220M parameters that agrees with gold human45;annotated preference labels more often than GPT45;4. The contributions of this work include training a standalone preference model that can score human45; and LLM45;generated answers on the same scale; developing an axiomatic framework for generating training data pairs tailored to certain principles; and showing that a small amount of axiomatic signals can help small models outperform GPT45;4 in preference scoring. We release our model on huggingface https://huggingface.co/corbyrosset/axiomatic&#95;preference&#95;model
