---
layout: publication
title: Bbox45;adapter Lightweight Adapting For Black45;box Large Language Models
authors: Sun Haotian, Zhuang Yuchen, Wei Wei, Zhang Chao, Dai Bo
conference: "Arxiv"
year: 2024
bibkey: sun2024bbox
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.08219"}
tags: ['Efficiency And Optimization', 'Ethics And Bias', 'GPT', 'Model Architecture', 'Tools', 'Training Techniques']
---
Adapting state45;of45;the45;art Large Language Models (LLMs) like GPT45;4 and Gemini for specific tasks is challenging. Due to the opacity in their parameters embeddings and even output probabilities existing fine45;tuning adaptation methods are inapplicable. Consequently adapting these black45;box LLMs is only possible through their API services raising concerns about transparency privacy and cost. To address these challenges we introduce BBox45;Adapter a novel lightweight adapter for black45;box LLMs. BBox45;Adapter distinguishes target and source domain data by treating target data as positive and source data as negative. It employs a ranking45;based Noise Contrastive Estimation (NCE) loss to promote the likelihood of target domain data while penalizing that of the source domain. Furthermore it features an online adaptation mechanism which incorporates real45;time positive data sampling from ground45;truth human or AI feedback coupled with negative data from previous adaptations. Extensive experiments demonstrate BBox45;Adapters effectiveness and cost efficiency. It improves model performance by up to 6.7737; across diverse tasks and domains while reducing training and inference costs by 31.30x and 1.84x respectively.
