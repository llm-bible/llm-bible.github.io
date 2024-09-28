---
layout: publication
title: Evaluating ChatGPT as a Recommender System A Rigorous Approach
authors: Di Palma Dario, Biancofiore Giovanni Maria, Anelli Vito Walter, Narducci Fedelucio, Di Noia Tommaso, Di Sciascio Eugenio
conference: "Arxiv"
year: 2023
bibkey: dipalma2023evaluating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.03613"}
tags: ['ARXIV', 'Applications', 'Few Shot', 'Prompt', 'Tools']
---
Large Language Models (LLMs) have recently shown impressive abilities in handling various natural language-related tasks. Among different LLMs current studies have assessed ChatGPTs superior performance across manifold tasks especially under the zero/few-shot prompting conditions. Given such successes the Recommender Systems (RSs) research community have started investigating its potential applications within the recommendation scenario. However although various methods have been proposed to integrate ChatGPTs capabilities into RSs current research struggles to comprehensively evaluate such models while considering the peculiarities of generative models. Often evaluations do not consider hallucinations duplications and out-of-the-closed domain recommendations and solely focus on accuracy metrics neglecting the impact on beyond-accuracy facets. To bridge this gap we propose a robust evaluation pipeline to assess ChatGPTs ability as an RS and post-process ChatGPT recommendations to account for these aspects. Through this pipeline we investigate ChatGPT-3.5 and ChatGPT-4 performance in the recommendation task under the zero-shot condition employing the role-playing prompt. We analyze the models functionality in three settings the Top-N Recommendation the cold-start recommendation and the re-ranking of a list of recommendations and in three domains movies music and books. The experiments reveal that ChatGPT exhibits higher accuracy than the baselines on books domain. It also excels in re-ranking and cold-start scenarios while maintaining reasonable beyond-accuracy metrics. Furthermore we measure the similarity between the ChatGPT recommendations and the other recommenders providing insights about how ChatGPT could be categorized in the realm of recommender systems. The evaluation pipeline is publicly released for future research.
