---
layout: publication
title: 'Distilling Desired Comments For Enhanced Code Review With Large Language Models'
authors: Yongda Yu, Lei Zhang, Guoping Rong, Haifeng Shen, Jiahao Zhang, Haoxiang Yan, Guohao Shi, Dong Shao, Ruiqi Pan, Yuan Li, Qiushi Wang, Zhao Tian
conference: "Arxiv"
year: 2024
bibkey: yu2024distilling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.20340"}
tags: ['Training Techniques', 'Efficiency and Optimization', 'Distillation', 'Survey Paper']
---
There has been a growing interest in using Large Language Models (LLMs) for
code review thanks to their proven proficiency in code comprehension. The
primary objective of most review scenarios is to generate desired review
comments (DRCs) that explicitly identify issues to trigger code fixes. However,
existing LLM-based solutions are not so effective in generating DRCs for
various reasons such as hallucination. To enhance their code review ability,
they need to be fine-tuned with a customized dataset that is ideally full of
DRCs. Nevertheless, such a dataset is not yet available, while manual
annotation of DRCs is too laborious to be practical. In this paper, we propose
a dataset distillation method, Desiview, which can automatically construct a
distilled dataset by identifying DRCs from a code review dataset. Experiments
on the CodeReviewer dataset comprising more than 150K review entries show that
Desiview achieves an impressive performance of 88.93%, 80.37%, 86.67%, and
84.44% in terms of Precision, Recall, Accuracy, and F1, respectively,
surpassing state-of-the-art methods. To validate the effect of such a distilled
dataset on enhancing LLMs' code review ability, we first fine-tune the latest
LLaMA series (i.e., LLaMA 3 and LLaMA 3.1) to build model Desiview4FT. We then
enhance the model training effect through KTO alignment by feeding those review
comments identified as non-DRCs to the LLMs, resulting in model Desiview4FA.
Verification results indicate that Desiview4FA slightly outperforms
Desiview4FT, while both models have significantly improved against the base
models in terms of generating DRCs. Human evaluation confirms that both models
identify issues more accurately and tend to generate review comments that
better describe the issues contained in the code than the base LLMs do.
