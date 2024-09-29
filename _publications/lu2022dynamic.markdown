---
layout: publication
title: Dynamic Prompt Learning Via Policy Gradient For Semi45;structured Mathematical Reasoning
authors: Pan Lu, Liang Qiu, Kai-wei Chang, Ying Nian Wu, Song-chun Zhu, Tanmay Rajpurohit, Peter Clark, Ashwin Kalyan
conference: "Arxiv"
year: 2022
bibkey: lu2022dynamic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/http://arxiv.org/abs/2209.14610v3"}
tags: ['GPT', 'Model Architecture', 'Prompting', 'Reinforcement Learning', 'Training Techniques']
---
Mathematical reasoning a core ability of human intelligence presents unique challenges for machines in abstract thinking and logical reasoning. Recent large pre45;trained language models such as GPT45;3 have achieved remarkable progress on mathematical reasoning tasks written in text form such as math word problems (MWP). However it is unknown if the models can handle more complex problems that involve math reasoning over heterogeneous information such as tabular data. To fill the gap we present Tabular Math Word Problems (TabMWP) a new dataset containing 38431 open45;domain grade45;level problems that require mathematical reasoning on both textual and tabular data. Each question in TabMWP is aligned with a tabular context which is presented as an image semi45;structured text and a structured table. There are two types of questions free45;text and multi45;choice and each problem is annotated with gold solutions to reveal the multi45;step reasoning process. We evaluate different pre45;trained models on TabMWP including the GPT45;3 model in a few45;shot setting. As earlier studies suggest since few45;shot GPT45;3 relies on the selection of in45;context examples its performance is unstable and can degrade to near chance. The unstable issue is more severe when handling complex problems like TabMWP. To mitigate this we further propose a novel approach PromptPG which utilizes policy gradient to learn to select in45;context examples from a small amount of training data and then constructs the corresponding prompt for the test example. Experimental results show that our method outperforms the best baseline by 5.3137; on the accuracy metric and reduces the prediction variance significantly compared to random selection which verifies its effectiveness in selecting in45;context examples.
