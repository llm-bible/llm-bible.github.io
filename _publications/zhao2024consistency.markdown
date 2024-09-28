---
layout: publication
title: Consistency Matters Explore LLMs Consistency From a Black-Box Perspective
authors: Zhao Fufangchen, Jin Guoqiang, Huang Jiaheng, Zhao Rui, Tan Fei
conference: "Arxiv"
year: 2024
bibkey: zhao2024consistency
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.17411"}
  - {name: "Code", url: "https://github.com/heavenhellchen/Consistency.git"}
tags: ['ARXIV', 'GPT', 'Has Code', 'LLM', 'Model Architecture', 'NLP', 'Tools']
---
Nowadays both commercial and open-source academic LLM have become the mainstream models of NLP. However there is still a lack of research on LLM consistency meaning that throughout the various stages of LLM research and deployment its internal parameters and capabilities should remain unchanged. This issue exists in both the industrial and academic sectors. The solution to this problem is often time-consuming and labor-intensive and there is also an additional cost of secondary deployment resulting in economic and time losses. To fill this gap we build an LLM consistency task dataset and design several baselines. Additionally we choose models of diverse scales for the main experiments. Specifically in the LightGBM experiment we used traditional NLG metrics (i.e. ROUGE BLEU METEOR) as the features needed for model training. The final result exceeds the manual evaluation and GPT3.5 as well as other models in the main experiment achieving the best performance. In the end we use the best performing LightGBM model as the base model to build the evaluation tool which can effectively assist in the deployment of business models. Our code and tool demo are available at https://github.com/heavenhellchen/Consistency.git
