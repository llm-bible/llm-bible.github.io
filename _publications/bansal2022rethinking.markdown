---
layout: publication
title: Rethinking The Role Of Scale For In45;context Learning An Interpretability45;based Case Study At 66 Billion Scale
authors: Bansal Hritik, Gopalakrishnan Karthik, Dingliwal Saket, Bodapati Sravan, Kirchhoff Katrin, Roth Dan
conference: "Arxiv"
year: 2022
bibkey: bansal2022rethinking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2212.09095"}
tags: ['Attention Mechanism', 'Interpretability And Explainability', 'Model Architecture', 'Prompting', 'Reinforcement Learning']
---
Language models have been shown to perform better with an increase in scale on a wide variety of tasks via the in45;context learning paradigm. In this paper we investigate the hypothesis that the ability of a large language model to in45;context learn45;perform a task is not uniformly spread across all of its underlying components. Using a 66 billion parameter language model (OPT45;66B) across a diverse set of 14 downstream tasks we find this is indeed the case sim7037; of attention heads and sim2037; of feed forward networks can be removed with minimal decline in task performance. We find substantial overlap in the set of attention heads (un)important for in45;context learning across tasks and number of in45;context examples. We also address our hypothesis through a task45;agnostic lens finding that a small set of attention heads in OPT45;66B score highly on their ability to perform primitive induction operations associated with in45;context learning namely prefix matching and copying. These induction heads overlap with task45;specific important heads reinforcing arguments by Olsson et al. (arXiv2209.11895) regarding induction head generality to more sophisticated behaviors associated with in45;context learning. Overall our study provides several insights that indicate large language models may be under45;trained for in45;context learning and opens up questions on how to pre45;train language models to more effectively perform in45;context learning.
