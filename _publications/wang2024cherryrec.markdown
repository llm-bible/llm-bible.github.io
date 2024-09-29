---
layout: publication
title: CherryRec Enhancing News Recommendation Quality via LLM-driven Framework
authors: Wang Shaohuang, Wang Lun, Bu Yunhan, Huang Tianwei
conference: "Arxiv"
year: 2024
bibkey: wang2024cherryrec
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.12243"}
tags: ['Efficiency And Optimization', 'Pretraining Methods', 'RAG', 'Tools']
---
Large Language Models (LLMs) have achieved remarkable progress in language understanding and generation. Custom LLMs leveraging textual features have been applied to recommendation systems demonstrating improvements across various recommendation scenarios. However most existing methods perform untrained recommendation based on pre-trained knowledge (e.g. movie recommendation) and the auto-regressive generation of LLMs leads to slow inference speeds making them less effective in real-time recommendations.To address this we propose a framework for news recommendation using LLMs named which ensures the quality of recommendations while accelerating the recommendation process. Specifically we employ a Knowledge-aware News Rapid Selector to retrieve candidate options based on the users interaction history. The history and retrieved items are then input as text into a fine-tuned LLM the Content-aware News Llm Evaluator designed to enhance news recommendation capabilities. Finally the Value-aware News Scorer integrates the scores to compute the CherryRec Score which serves as the basis for the final recommendation.We validate the effectiveness of the proposed framework by comparing it with state-of-the-art baseline methods on benchmark datasets. Our experimental results consistently show that CherryRec outperforms the baselines in both recommendation performance and efficiency.The project resource can be accessed at
