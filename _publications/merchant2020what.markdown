---
layout: publication
title: What Happens To BERT Embeddings During Fine45;tuning
authors: Merchant Amil, Rahimtoroghi Elahe, Pavlick Ellie, Tenney Ian
conference: "Arxiv"
year: 2020
bibkey: merchant2020what
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2004.14448"}
tags: ['BERT', 'Efficiency And Optimization', 'Model Architecture']
---
While there has been much recent work studying how linguistic information is encoded in pre45;trained sentence representations comparatively little is understood about how these models change when adapted to solve downstream tasks. Using a suite of analysis techniques (probing classifiers Representational Similarity Analysis and model ablations) we investigate how fine45;tuning affects the representations of the BERT model. We find that while fine45;tuning necessarily makes significant changes it does not lead to catastrophic forgetting of linguistic phenomena. We instead find that fine45;tuning primarily affects the top layers of BERT but with noteworthy variation across tasks. In particular dependency parsing reconfigures most of the model whereas SQuAD and MNLI appear to involve much shallower processing. Finally we also find that fine45;tuning has a weaker effect on representations of out45;of45;domain sentences suggesting room for improvement in model generalization.
