---
layout: publication
title: 'Meta-rater: A Multi-dimensional Data Selection Method For Pre-training Language Models'
authors: Xinlin Zhuang, Jiahui Peng, Ren Ma, Yinfan Wang, Tianyi Bai, Xingjian Wei, Jiantao Qiu, Chi Zhang, Ying Qian, Conghui He
conference: "Arxiv"
year: 2025
bibkey: zhuang2025meta
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.14194"}
  - {name: "Code", url: "https://github.com/opendatalab/Meta-rater"}
tags: ['Pre-Training', 'Efficiency and Optimization', 'Ethics and Bias', 'Interpretability', 'Training Techniques', 'Has Code']
---
The composition of pre-training datasets for large language models (LLMs) remains largely undisclosed, hindering transparency and efforts to optimize data quality, a critical driver of model performance. Current data selection methods, such as natural language quality assessments, diversity-based filters, and classifier-based approaches, are limited by single-dimensional evaluation or redundancy-focused strategies. To address these gaps, we propose four dimensions to evaluate data quality: professionalism, readability, reasoning, and cleanliness. We further introduce Meta-rater,a multi-dimensional data selection method that integrates these dimensions with existing quality metrics through learned optimal weightings. Meta-rater employs proxy models to train a regression model that predicts validation loss, enabling the identification of optimal combinations of quality scores. Experiments demonstrate that Meta-rater doubles convergence speed for 1.3B parameter models and improves downstream task performance by 3.23, with advantages that scale to models as large as 7.2B parameters. Our work establishes that holistic, multi-dimensional quality integration significantly outperforms conventional single-dimension approaches, offering a scalable paradigm for enhancing pre-training efficiency and model capability. To advance future research, we release scripts, data, and models at https://github.com/opendatalab/Meta-rater.
