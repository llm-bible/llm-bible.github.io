---
layout: publication
title: 'TALEC: Teach Your LLM To Evaluate In Specific Domain With In-house Criteria By Criteria Division And Zero-shot Plus Few-shot'
authors: Kaiqi Zhang, Shuai Yuan, Honghan Zhao
conference: "Arxiv"
year: 2024
bibkey: zhang2024teach
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.10999"}
  - {name: "Code", url: "https://github.com/zlkqz/auto_eval"}
tags: ['Fine-Tuning', 'Tools', 'Applications', 'Language Modeling', 'Security', 'Training Techniques', 'Has Code', 'Pretraining Methods', 'Few-Shot', 'Prompting', 'In-Context Learning']
---
With the rapid development of large language models (LLM), the evaluation of
LLM becomes increasingly important. Measuring text generation tasks such as
summarization and article creation is very difficult. Especially in specific
application domains (e.g., to-business or to-customer service), in-house
evaluation criteria have to meet not only general standards (correctness,
helpfulness and creativity, etc.) but also specific needs of customers and
business security requirements at the same time, making the evaluation more
difficult. So far, the evaluation of LLM in business scenarios has mainly
relied on manual, which is expensive and time-consuming. In this paper, we
propose a model-based evaluation method: TALEC, which allows users to flexibly
set their own evaluation criteria, and uses in-context learning (ICL) to teach
judge model these in-house criteria. In addition, we try combining zero-shot
and few-shot to make the judge model focus on more information. We also propose
a prompt paradigm and an engineering approach to adjust and iterate the shots
,helping judge model to better understand the complex criteria. We then compare
fine-tuning with ICL, finding that fine-tuning can be replaced by ICL. TALEC
demonstrates a strong capability to accurately reflect human preferences and
achieves a correlation of over 80% with human judgments, outperforming even the
inter-human correlation in some tasks. The code is released in
https://github.com/zlkqz/auto_eval
