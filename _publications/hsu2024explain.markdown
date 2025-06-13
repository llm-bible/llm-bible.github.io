---
layout: publication
title: 'Rate, Explain And Cite (REC): Enhanced Explanation And Attribution In Automatic Evaluation By Large Language Models'
authors: Aliyah R. Hsu, James Zhu, Zhichao Wang, Bin Bi, Shubham Mehrotra, Shiva K. Pentyala, Katherine Tan, Xiang-bo Mao, Roshanak Omrani, Sougata Chaudhuri, Regunathan Radhakrishnan, Sitaram Asur, Claire Na Cheng, Bin Yu
conference: "Arxiv"
year: 2024
bibkey: hsu2024explain
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.02448"}
  - {name: "Code", url: "https://github.com/adelaidehsu/REC"}
tags: ['Interpretability and Explainability', 'Has Code', 'Ethics and Bias', 'Reinforcement Learning']
---
LLMs have demonstrated impressive proficiency in generating coherent and high-quality text, making them valuable across a range of text-generation tasks. However, rigorous evaluation of this generated content is crucial, as ensuring its quality remains a significant challenge due to persistent issues such as factual inaccuracies and hallucination. This paper introduces three fine-tuned general-purpose LLM autoevaluators, REC-8B, REC-12B and REC-70B, specifically designed to evaluate generated text across several dimensions: faithfulness, instruction following, coherence, and completeness. These models not only provide ratings for these metrics but also offer detailed explanation and verifiable citation, thereby enhancing trust in the content. Moreover, the models support various citation modes, accommodating different requirements for latency and granularity. Extensive evaluations on diverse benchmarks demonstrate that our general-purpose LLM auto-evaluator, REC-70B, outperforms state-of-the-art LLMs, excelling in content evaluation by delivering better quality explanation and citation with minimal bias. Our REC dataset and models are available at https://github.com/adelaidehsu/REC.
