---
layout: publication
title: Knowledge-prompted Estimator: A Novel Approach To Explainable Machine Translation Assessment
authors: Yang Hao, Zhang Min, Tao Shimin, Wang Minghan, Wei Daimeng, Jiang Yanfei
conference: "Arxiv"
year: 2023
bibkey: yang2023knowledge
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2306.07486"}
tags: ['Applications', 'Interpretability And Explainability', 'Prompting', 'Reinforcement Learning']
---
Cross-lingual Machine Translation (MT) quality estimation plays a crucial role in evaluating translation performance. GEMBA the first MT quality assessment metric based on Large Language Models (LLMs) employs one-step prompting to achieve state-of-the-art (SOTA) in system-level MT quality estimation; however it lacks segment-level analysis. In contrast Chain-of-Thought (CoT) prompting outperforms one-step prompting by offering improved reasoning and explainability. In this paper we introduce Knowledge-Prompted Estimator (KPE) a CoT prompting method that combines three one-step prompting techniques including perplexity token-level similarity and sentence-level similarity. This method attains enhanced performance for segment-level estimation compared with previous deep learning models and one-step prompting approaches. Furthermore supplementary experiments on word-level visualized alignment demonstrate that our KPE method significantly improves token alignment compared with earlier models and provides better interpretability for MT quality estimation. Code will be released upon publication.
