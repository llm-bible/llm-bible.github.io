---
layout: publication
title: 'The Current Status Of Large Language Models In Summarizing Radiology Report Impressions'
authors: Danqing Hu, Shanyuan Zhang, Qing Liu, Xiaofeng Zhu, Bing Liu
conference: "Arxiv"
year: 2024
bibkey: hu2024current
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2406.02134'}
tags: ['Language Modeling', 'Few-Shot', 'GPT', 'Applications', 'Model Architecture', 'Prompting']
---
Large language models (LLMs) like ChatGPT show excellent capabilities in
various natural language processing tasks, especially for text generation. The
effectiveness of LLMs in summarizing radiology report impressions remains
unclear. In this study, we explore the capability of eight LLMs on the
radiology report impression summarization. Three types of radiology reports,
i.e., CT, PET-CT, and Ultrasound reports, are collected from Peking University
Cancer Hospital and Institute. We use the report findings to construct the
zero-shot, one-shot, and three-shot prompts with complete example reports to
generate the impressions. Besides the automatic quantitative evaluation
metrics, we define five human evaluation metrics, i.e., completeness,
correctness, conciseness, verisimilitude, and replaceability, to evaluate the
semantics of the generated impressions. Two thoracic surgeons (ZSY and LB) and
one radiologist (LQ) compare the generated impressions with the reference
impressions and score each impression under the five human evaluation metrics.
Experimental results show that there is a gap between the generated impressions
and reference impressions. Although the LLMs achieve comparable performance in
completeness and correctness, the conciseness and verisimilitude scores are not
very high. Using few-shot prompts can improve the LLMs' performance in
conciseness and verisimilitude, but the clinicians still think the LLMs can not
replace the radiologists in summarizing the radiology impressions.
