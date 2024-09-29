---
layout: publication
title: 'Aligning Large Language Models With Recommendation Knowledge'
authors: Cao Yuwei, Mehta Nikhil, Yi Xinyang, Keshavan Raghunandan, Heldt Lukasz, Hong Lichan, Chi Ed H., Sathiamoorthy Maheswaran
conference: "Arxiv"
year: 2024
bibkey: cao2024aligning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.00245"}
tags: ['Fine Tuning', 'Pretraining Methods', 'Training Techniques']
---
Large language models (LLMs) have recently been used as backbones for recommender systems. However their performance often lags behind conventional methods in standard tasks like retrieval. We attribute this to a mismatch between LLMs knowledge and the knowledge crucial for effective recommendations. While LLMs excel at natural language reasoning they cannot model complex user-item interactions inherent in recommendation tasks. We propose bridging the knowledge gap and equipping LLMs with recommendation-specific knowledge to address this. Operations such as Masked Item Modeling (MIM) and Bayesian Personalized Ranking (BPR) have found success in conventional recommender systems. Inspired by this we simulate these operations through natural language to generate auxiliary-task data samples that encode item correlations and user preferences. Fine-tuning LLMs on such auxiliary-task data samples and incorporating more informative recommendation-task data samples facilitates the injection of recommendation-specific knowledge into LLMs. Extensive experiments across retrieval ranking and rating prediction tasks on LLMs such as FLAN-T5-Base and FLAN-T5-XL show the effectiveness of our technique in domains such as Amazon Toys amp; Games Beauty and Sports amp; Outdoors. Notably our method outperforms conventional and LLM-based baselines including the current SOTA by significant margins in retrieval showcasing its potential for enhancing recommendation quality.
