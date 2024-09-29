---
layout: publication
title: Constructive Large Language Models Alignment With Diverse Feedback
authors: Yu Tianshu, Lin Ting-en, Wu Yuchuan, Yang Min, Huang Fei, Li Yongbin
conference: "Arxiv"
year: 2023
bibkey: yu2023constructive
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.06450"}
tags: ['Applications', 'Reinforcement Learning', 'Training Techniques']
---
In recent research on large language models (LLMs) there has been a growing emphasis on aligning these models with human values to reduce the impact of harmful content. However current alignment methods often rely solely on singular forms of human feedback such as preferences annotated labels or natural language critiques overlooking the potential advantages of combining these feedback types. This limitation leads to suboptimal performance even when ample training data is available. In this paper we introduce Constructive and Diverse Feedback (CDF) as a novel method to enhance LLM alignment inspired by constructivist learning theory. Our approach involves collecting three distinct types of feedback tailored to problems of varying difficulty levels within the training dataset. Specifically we exploit critique feedback for easy problems refinement feedback for medium problems and preference feedback for hard problems. By training our model with this diversified feedback we achieve enhanced alignment performance while using less training data. To assess the effectiveness of CDF we evaluate it against previous methods in three downstream tasks question answering dialog generation and text summarization. Experimental results demonstrate that CDF achieves superior performance even with a smaller training dataset.
