---
layout: publication
title: 'Rephrasing The Web: A Recipe For Compute And Data-efficient Language Modeling'
authors: Maini Pratyush, Seto Skyler, Bai He, Grangier David, Zhang Yizhe, Jaitly Navdeep
conference: "Arxiv"
year: 2024
bibkey: maini2024rephrasing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.16380"}
tags: ['Efficiency And Optimization', 'Language Modeling', 'Large Scale Training', 'Model Architecture', 'Prompting', 'RAG', 'Reinforcement Learning', 'Scaling Laws', 'Training Techniques']
---
"Large language models are trained on massive scrapes of the web, which are often unstructured, noisy, and poorly phrased. Current scaling laws show that learning from such data requires an abundance of both compute and data, which grows with the size of the model being trained. This is infeasible both because of the large compute costs and duration associated with pre-training, and the impending scarcity of high-quality data on the web. In this work, we propose Web Rephrase Augmented Pre-training (\(\textbf{WRAP}\)) that uses an off-the-shelf instruction-tuned model prompted to paraphrase documents on the web in specific styles such as like Wikipedia or in question-answer format to jointly pre-train LLMs on real and synthetic rephrases. First, we show that using WRAP on the C4 dataset, which is naturally noisy, speeds up pre-training by \(\sim3x\). At the same pre-training compute budget, it improves perplexity by more than 10&#37; on average across different subsets of the Pile, and improves zero-shot question answer accuracy across 13 tasks by more than 2&#37;. Second, we investigate the impact of the re-phrasing style on the performance of the model, offering insights into how the composition of the training data can impact the performance of LLMs in OOD settings. Our gains are attributed to the fact that re-phrased synthetic data has higher utility than just real data because it (i) incorporates style diversity that closely reflects downstream evaluation style, and (ii) has higher 'quality' than web-scraped data."
