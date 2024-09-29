---
layout: publication
title: Llamas Know What Gpts Dont Show Surrogate Models For Confidence Estimation
authors: Shrivastava Vaishnavi, Liang Percy, Kumar Ananya
conference: "Arxiv"
year: 2023
bibkey: shrivastava2023llamas
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.08877"}
tags: ['Applications', 'GPT', 'Model Architecture', 'RAG']
---
To maintain user trust large language models (LLMs) should signal low confidence on examples where they are incorrect instead of misleading the user. The standard approach of estimating confidence is to use the softmax probabilities of these models but as of November 2023 state45;of45;the45;art LLMs such as GPT45;4 and Claude45;v1.3 do not provide access to these probabilities. We first study eliciting confidence linguistically 45;45; asking an LLM for its confidence in its answer 45;45; which performs reasonably (80.537; AUC on GPT45;4 averaged across 12 question45;answering datasets 45;45; 737; above a random baseline) but leaves room for improvement. We then explore using a surrogate confidence model 45;45; using a model where we do have probabilities to evaluate the original models confidence in a given question. Surprisingly even though these probabilities come from a different and often weaker model this method leads to higher AUC than linguistic confidences on 9 out of 12 datasets. Our best method composing linguistic confidences and surrogate model probabilities gives state45;of45;the45;art confidence estimates on all 12 datasets (84.637; average AUC on GPT45;4).
