---
layout: publication
title: Tackling Vision Language Tasks Through Learning Inner Monologues
authors: Yang Diji, Chen Kezhen, Rao Jinmeng, Guo Xiaoyuan, Zhang Yawen, Yang Jie, Zhang Yi
conference: "Arxiv"
year: 2023
bibkey: yang2023tackling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2308.09970"}
tags: ['Efficiency And Optimization', 'Interpretability And Explainability', 'Merging', 'Training Techniques']
---
Visual language tasks require AI models to comprehend and reason with both visual and textual content. Driven by the power of Large Language Models (LLMs) two prominent methods have emerged (1) the hybrid integration between LLMs and Vision45;Language Models (VLMs) where visual inputs are firstly converted into language descriptions by VLMs serving as inputs for LLMs to generate final answer(s); (2) visual feature alignment in language space where visual inputs are encoded as embeddings and projected to LLMs language space via further supervised fine45;tuning. The first approach provides light training costs and interpretability but is hard to be optimized in an end45;to45;end fashion. The second approach presents decent performance but feature alignment usually requires large amounts of training data and lacks interpretability. To tackle this dilemma we propose a novel approach Inner Monologue Multi45;Modal Optimization (IMMO) to solve complex vision language problems by simulating inner monologue processes a cognitive process in which an individual engages in silent verbal communication with themselves. We enable LLMs and VLMs to interact through natural language conversation and propose to use a two45;stage training process to learn how to do the inner monologue (self45;asking questions and answering questions). IMMO is evaluated on two popular tasks and the results suggest by emulating the cognitive phenomenon of internal dialogue our approach can enhance reasoning and explanation abilities contributing to the more effective fusion of vision and language models. More importantly instead of using predefined human45;crafted monologues IMMO learns this process within the deep learning models promising wider applicability to many different AI problems beyond vision language tasks.
