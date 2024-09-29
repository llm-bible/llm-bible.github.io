---
layout: publication
title: Can We Edit Factual Knowledge By In45;context Learning
authors: Zheng Ce, Li Lei, Dong Qingxiu, Fan Yuxuan, Wu Zhiyong, Xu Jingjing, Chang Baobao
conference: "Arxiv"
year: 2023
bibkey: zheng2023can
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.12740"}
  - {name: "Code", url: "https://github.com/Zce1112zslx/IKE"}
tags: ['GPT', 'Has Code', 'Model Architecture', 'Prompting']
---
Previous studies have shown that large language models (LLMs) like GPTs store massive factual knowledge in their parameters. However the stored knowledge could be false or out45;dated. Traditional knowledge editing methods refine LLMs via fine45;tuning on texts containing specific knowledge. However with the increasing scales of LLMs these gradient45;based approaches bring large computation costs. The trend of model45;as45;a45;service also makes it impossible to modify knowledge in black45;box LMs. Inspired by in45;context learning (ICL) a new paradigm based on demonstration contexts without parameter updating we explore whether ICL can edit factual knowledge. To answer this question we give a comprehensive empirical study of ICL strategies. Experiments show that in45;context knowledge editing (IKE) without any gradient and parameter updating achieves a competitive success rate compared to gradient45;based methods on GPT45;J (6B) but with much fewer side effects including less over45;editing on similar but unrelated facts and less knowledge forgetting on previously stored knowledge. We also apply the method to larger LMs with tens or hundreds of parameters like OPT45;175B which shows the scalability of our method. The code is available at https://github.com/Zce1112zslx/IKE.
