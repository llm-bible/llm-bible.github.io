---
layout: publication
title: Data Augmentation For Intent Classification With Off45;the45;shelf Large Language Models
authors: Sahu Gaurav, Rodriguez Pau, Laradji Issam H., Atighehchian Parmida, Vazquez David, Bahdanau Dzmitry
conference: "Arxiv"
year: 2022
bibkey: sahu2022data
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2204.01959"}
tags: ['GPT', 'Model Architecture', 'Prompting', 'Training Techniques']
---
Data augmentation is a widely employed technique to alleviate the problem of data scarcity. In this work we propose a prompting45;based approach to generate labelled training data for intent classification with off45;the45;shelf language models (LMs) such as GPT45;3. An advantage of this method is that no task45;specific LM45;fine45;tuning for data generation is required; hence the method requires no hyper45;parameter tuning and is applicable even when the available training data is very scarce. We evaluate the proposed method in a few45;shot setting on four diverse intent classification tasks. We find that GPT45;generated data significantly boosts the performance of intent classifiers when intents in consideration are sufficiently distinct from each other. In tasks with semantically close intents we observe that the generated data is less helpful. Our analysis shows that this is because GPT often generates utterances that belong to a closely45;related intent instead of the desired one. We present preliminary evidence that a prompting45;based GPT classifier could be helpful in filtering the generated data to enhance its quality.
